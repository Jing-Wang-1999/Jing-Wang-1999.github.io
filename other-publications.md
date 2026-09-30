---
layout: default
title: Co-authored papers
permalink: /other-publications.html
---

<header class="page-intro">
  <p class="eyebrow">Publications / Collaboration</p>
  <h1>Co-authored papers</h1>
  <p>Additional research collaborations across RTL generation, circuit models, verification, and design automation.</p>
</header>

{% assign year_groups = site.data.publications.co_authored | group_by: 'year' %}
{% for year_group in year_groups %}
<section class="year-group" aria-labelledby="year-{{ year_group.name }}">
  <h2 class="year-group__title" id="year-{{ year_group.name }}">{{ year_group.name }}</h2>
  <div class="paper-list">
    {% for paper in year_group.items %}
      {% include publication-card.html paper=paper %}
    {% endfor %}
  </div>
</section>
{% endfor %}

<a class="section-link" href="{{ '/' | relative_url }}#publications"><span aria-hidden="true">←</span> Back to first-author papers</a>
