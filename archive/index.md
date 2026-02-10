---
layout: default
title: Archive
---

<div class="archive">
 <ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color:#777; font-size:0.9em;">
        — {{ post.date | date: "%B %d, %Y" }}
      </span>
    </li>
  {% endfor %}
</ul>
      <div class="archive-text">
        <div class="archive-title">{{ post.title }}</div>
        <div class="archive-meta">{{ post.date | date: "%B %d, %Y" }}</div>
        <div class="archive-excerpt">
          {{ post.excerpt | markdownify | strip_html | truncate: 240 }}
        </div>
      </div>
    </a>
  {% endfor %}
</div>
