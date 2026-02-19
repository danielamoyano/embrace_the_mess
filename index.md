---
layout: default
title: Embrace the Research Mess
body_class: home
---

<div class="home-collage" aria-hidden="true">
  {% for post in site.posts limit: 8 %}
    {% if post.hero %}
      <a class="home-poster" href="{{ post.url | relative_url }}">
        <img src="{{ post.hero | relative_url }}" alt="">
      </a>
    {% endif %}
  {% endfor %}
</div>

<section class="home-overlay">
  <h1>Embrace the Mess</h1>
  <p class="home-lede">A PhD journal in progress...</p>

  <hr>

  <h3>What this is</h3>
  <p>
    This is a working online notebook that makes visible how research is continuously taking shape.
    I document ideas while they are still forming: thoughts, visual models, diagrams, sketches, everyday objects—everything that contributes to the development of my research.
  </p>
  <p>
    I am exploring new ways of transmitting knowledge, and this online journal is part of that process.
  </p>

  <h3>How to read it</h3>
  <ul>
    <li><strong>Journal entries</strong>: week-to-week thinking</li>
    <li><strong>ARO's library</strong>: a collection of alternative ways of transmitting knowledge beyond academic journal articles</li>
  </ul>
</section>
