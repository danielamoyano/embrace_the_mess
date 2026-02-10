---
layout: default
title: Embrace the Research Mess
---

# Embrace the Mess

A PhD journal in progress...

---

### What this is
This is a working online notebook that makes visible how research is continuously taking shape.
I document ideas while they are still forming: thoughts, visual models, diagrams, sketches, everyday objects—everything that contributes to the development of my research.

I am exploring new ways of transmitting knowledge, and this online journal is part of that process.

### How to read it
- **Journal entries**: week-to-week thinking
- **ARO's library**: a collection of alternative ways of transmitting knowledge beyond academic journal articles

### Recent entries
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
      <span style="color:#777; font-size:0.9em;">
        — {{ post.date | date: "%B %d, %Y" }}
      </span>
    </li>
  {% endfor %}
</ul>