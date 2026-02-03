---
layout: default
title: 每日热门
permalink: /daily/
---
<style>
  h1 { margin-bottom: 1.5rem; }
  .calendar { display: flex; flex-direction: column; gap: 1.5rem; }
  .month-group h2 {
    font-size: 1rem;
    color: var(--text-muted);
    margin-bottom: 0.8rem;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid var(--border);
  }
  .days { display: grid; grid-template-columns: repeat(auto-fill, minmax(120px, 1fr)); gap: 0.5rem; }
  .day {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 0.8rem;
    text-align: center;
    transition: border-color 0.2s;
  }
  .day:hover { border-color: var(--accent); }
  .day-date { font-weight: 600; }
  .day-count { font-size: 0.8rem; color: var(--text-muted); }
</style>

<h1>🔥 每日热门</h1>

{% assign daily_by_month = site.daily | group_by_exp: "post", "post.date | date: '%Y-%m'" %}
{% assign sorted_months = daily_by_month | sort: 'name' | reverse %}

<div class="calendar">
{% for month in sorted_months %}
  <div class="month-group">
    <h2>{{ month.name }}</h2>
    <div class="days">
      {% assign sorted_days = month.items | sort: 'date' | reverse %}
      {% for post in sorted_days %}
      <a href="{{ post.url | relative_url }}" class="day">
        <div class="day-date">{{ post.date | date: "%d" }}日</div>
        <div class="day-count">{{ post.summary_count | default: 1 }} 条总结</div>
      </a>
      {% endfor %}
    </div>
  </div>
{% endfor %}
</div>

{% if site.daily.size == 0 %}
<p style="color: var(--text-muted); text-align: center; padding: 3rem;">暂无数据，热门内容总结会每2小时自动更新</p>
{% endif %}
