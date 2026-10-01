---
layout: default
title: Jing Wang
---

<section class="hero" id="about">
  <h1>Jing Wang <span>(王京)</span></h1>
  <p class="hero__lead">I am a PhD student in Electrical and Computer Engineering (ECE) at the Hong Kong University of Science and Technology (HKUST). My research explores how AI can support RTL generation, circuit reasoning, and design automation. You can also call me Sebastian.</p>
  <div class="hero__profiles">
    <a href="https://scholar.google.com/citations?user=KSnhcBIAAAAJ&amp;hl=en">Google Scholar <span aria-hidden="true">↗</span></a>
    <a href="https://github.com/Jing-Wang-1999">GitHub <span aria-hidden="true">↗</span></a>
  </div>
  <div class="focus-row" aria-label="Research interests">
    <span class="focus-row__label">Research areas</span>
    <div class="focus-list">
      <span>RTL generation</span>
      <span>AI for EDA</span>
      <span>Circuit foundation models</span>
    </div>
  </div>
</section>

<section class="content-section" id="education" aria-labelledby="education-title">
  <div class="section-heading">
    <h2 id="education-title">01 / Education</h2>
  </div>
  <div class="education-list">
    <div class="education-item">
      <span class="education-item__years">2024–present</span>
      <div>
        <h3>PhD in Electrical and Computer Engineering (ECE)</h3>
        <p>Hong Kong University of Science and Technology</p>
      </div>
    </div>
    <div class="education-item">
      <span class="education-item__years">2022–2024</span>
      <div>
        <h3>Master of Science in Artificial Intelligence</h3>
        <p>The University of Hong Kong</p>
      </div>
    </div>
    <div class="education-item">
      <span class="education-item__years">2018–2022</span>
      <div>
        <h3>Bachelor of Science in Electrical Information Engineering</h3>
        <p>Peking University</p>
      </div>
    </div>
  </div>
</section>

<section class="content-section" id="publications" aria-labelledby="publications-title">
  <div class="section-heading">
    <h2 id="publications-title">02 / Publications</h2>
    <p>First-author papers</p>
  </div>
  <div class="paper-list">
    {% for paper in site.data.publications.first_author %}
      {% include publication-card.html paper=paper %}
    {% endfor %}
  </div>
  <a class="section-link" href="{{ '/other-publications.html' | relative_url }}">Browse co-authored papers <span aria-hidden="true">→</span></a>
</section>
