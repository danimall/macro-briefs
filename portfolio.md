---
layout: default
title: Portfolio Recommendations
---

<div class="home">
  <p>AI-generated daily portfolio recommendations based on macro intelligence analysis.</p>

  <p><a href="/">Macro Briefs</a> &middot; <a href="/reports">Reports</a> &middot; <a href="/search">Search</a> &middot; <a href="/feed.xml">RSS Feed</a></p>

  <h2>Portfolio History</h2>

  <ul class="post-list">
    {%- for rec in site.portfolios reversed -%}
    <li>
      <a href="{{ rec.url | relative_url }}">{{ rec.title }}</a>
      <small style="color: #888;">{{ rec.date | date: "%B %-d, %Y at %-I:%M %p" }}</small>
    </li>
    {%- endfor -%}
  </ul>
</div>
