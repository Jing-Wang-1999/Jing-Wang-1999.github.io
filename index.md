---
layout: default
title: Jing Wang
---

<header class="introduction">
  <h1>Jing Wang <span lang="zh-Hans">(王京)</span></h1>
  <p>I am a PhD student in Electrical and Computer Engineering at the Hong Kong University of Science and Technology. My research focuses on AI for electronic design automation, including RTL generation and circuit reasoning. I also go by Sebastian.</p>
</header>

<section class="content-section" id="background" aria-labelledby="background-title">
  <h2 class="section-title" id="background-title"><span>01</span> Background</h2>
  <h3 class="subsection-title">Education</h3>
  <div class="detail-list">
    <div class="detail-item">
      <span class="detail-item__year">2024–present</span>
      <div>
        <h4>PhD in Electrical and Computer Engineering</h4>
        <p>Hong Kong University of Science and Technology</p>
      </div>
    </div>
    <div class="detail-item">
      <span class="detail-item__year">2022–2024</span>
      <div>
        <h4>Master of Science in Artificial Intelligence</h4>
        <p>The University of Hong Kong</p>
      </div>
    </div>
    <div class="detail-item">
      <span class="detail-item__year">2019–2023</span>
      <div>
        <h4>Bachelor of Science in Electrical Information Engineering</h4>
        <p>Peking University</p>
      </div>
    </div>
  </div>
</section>

<section class="content-section" id="research" aria-labelledby="research-title">
  <h2 class="section-title" id="research-title"><span>02</span> Research</h2>
  <h3 class="subsection-title">First-author publications</h3>
  <div class="publication-list">
    {% for paper in site.data.publications.first_author %}
      {% include publication-row.html paper=paper %}
    {% endfor %}
  </div>

  <h3 class="subsection-title subsection-title--continued" id="co-authored">Co-authored papers</h3>
  <div class="publication-list">
    {% for paper in site.data.publications.co_authored %}
      {% include publication-row.html paper=paper %}
    {% endfor %}
  </div>
</section>
