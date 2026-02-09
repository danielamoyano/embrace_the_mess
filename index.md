---
layout: default
title: Embrace the Research Mess
---

# Embrace the Mess

A PhD journal in progress — notes, sketches, diagrams, and experiments on how knowledge travels.

---

### What this is
This is a working notebook.
I’m documenting ideas while they’re still forming: incomplete thoughts, visual models, failures, and small breakthroughs.

I’m researching new ways of transmitting knowledge — so the format is part of the experiment.

---

### How to read it
- **Journal entries**: day-to-day thinking and progress
- **Experiments**: attempts at visual/interactive transmission
- **Fragments**: raw notes worth keeping

---

### Recent entries
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
      <span style="color:#777; font-size:0.9em;">
        — {{ post.date | date: "%B %d, %Y" }}
      </span>
    </li>
  {% endfor %}
</ul>