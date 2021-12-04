---
layout: default
title: Research
permalink: /research/
---

<section class="hero">
  <div class="hero-body">
    <div class="title">Publications</div>
    <p class="subtitle mt-4">
      {% for pub in site.data.publications %}
        <div class="container is-fluid mt-2 mb-2">
          <a href="{{pub.url}}"><b>{{pub.title}}</b></a>;&nbsp;<i>{{pub.author}}</i>;&nbsp;{{pub.journal}};&nbsp;{{pub.year}};&nbsp;DOI: {{pub.doi}}
        </div>
      {% endfor %}
    </p>
  </div>
</section>
