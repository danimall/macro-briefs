---
layout: default
title: Research Reports
---

<div class="home">
  <p>AI-generated company research reports with scoring across six dimensions and actionable recommendations.</p>

  <p><a href="/">Macro Briefs</a> &middot; <a href="/portfolio">Portfolio</a> &middot; <a href="/search">Search</a> &middot; <a href="/feed.xml">RSS Feed</a></p>

  <h2>Reports</h2>

  <input type="text" id="report-search" placeholder="Search by ticker or company..." style="width: 100%; padding: 8px; font-size: 16px; margin-bottom: 20px; box-sizing: border-box;">

  <table style="width:100%; border-collapse:collapse; font-size:14px;">
    <tr style="border-bottom:2px solid #ddd;">
      <th style="text-align:left; padding:8px 12px; cursor:pointer;" onclick="sortReports('ticker')">Ticker</th>
      <th style="text-align:left; padding:8px 12px; cursor:pointer;" onclick="sortReports('company')">Company</th>
      <th style="text-align:left; padding:8px 12px; cursor:pointer;" onclick="sortReports('score')">Score</th>
      <th style="text-align:left; padding:8px 12px; cursor:pointer;" onclick="sortReports('recommendation')">Rec</th>
      <th style="text-align:left; padding:8px 12px; cursor:pointer;" onclick="sortReports('date')">Date</th>
    </tr>
    <tbody id="reports-body">
    {%- for report in site.reports reversed -%}
    <tr class="report-row" data-ticker="{{ report.ticker | downcase }}" data-company="{{ report.company | downcase }}" data-score="{{ report.score }}" data-rec="{{ report.recommendation }}" data-date="{{ report.date | date: '%Y%m%d' }}" style="border-bottom:1px solid #eee;">
      <td style="padding:8px 12px; font-weight:600;"><a href="{{ report.url | relative_url }}">{{ report.ticker }}</a></td>
      <td style="padding:8px 12px;">{{ report.company }}</td>
      <td style="padding:8px 12px;">{{ report.score }}/10</td>
      <td style="padding:8px 12px;">{{ report.recommendation }}</td>
      <td style="padding:8px 12px;">{{ report.date | date: "%b %-d, %Y" }}</td>
    </tr>
    {%- endfor -%}
    </tbody>
  </table>
</div>

<script>
var searchInput = document.getElementById("report-search");
searchInput.addEventListener("input", function() {
  var q = this.value.toLowerCase().trim();
  document.querySelectorAll(".report-row").forEach(function(row) {
    var ticker = row.getAttribute("data-ticker");
    var company = row.getAttribute("data-company");
    row.style.display = (!q || ticker.indexOf(q) !== -1 || company.indexOf(q) !== -1) ? "" : "none";
  });
});

var currentSort = "date";
var sortAsc = false;
function sortReports(col) {
  if (currentSort === col) { sortAsc = !sortAsc; } else { currentSort = col; sortAsc = col === "ticker"; }
  var tbody = document.getElementById("reports-body");
  var rows = Array.from(tbody.querySelectorAll(".report-row"));
  rows.sort(function(a, b) {
    var va = a.getAttribute("data-" + col);
    var vb = b.getAttribute("data-" + col);
    if (col === "score") { va = parseFloat(va) || 0; vb = parseFloat(vb) || 0; }
    if (va < vb) return sortAsc ? -1 : 1;
    if (va > vb) return sortAsc ? 1 : -1;
    return 0;
  });
  rows.forEach(function(row) { tbody.appendChild(row); });
}
</script>
