---
layout: academic
title: lihaozhe
---
<section class="hero" id="about" aria-labelledby="intro-title">
  <div class="hero-copy">
    <p class="eyebrow"><span class="small-line"></span> PERSONAL &amp; ACADEMIC</p>
    <h1 id="intro-title">lihaozhe</h1>
    <p class="hero-focus">几何拓扑 <span>×</span> Math for AI</p>
    <p class="intro">关注几何拓扑与人工智能相关的数学。<br class="desktop-break">这里汇集我的学习思考、科研心得与个人作品。</p>
    <div class="hero-links">
      <a class="button" href="#research">研究兴趣 <span aria-hidden="true">↗</span></a>
      <a class="text-link" href="https://github.com/weinmanwodskow453-cpu">GitHub <span aria-hidden="true">↗</span></a>
    </div>
  </div>
  <figure class="portrait-wrap">
    <div class="portrait-frame"><img src="{{ '/assets/images/portrait.jpg' | relative_url }}" alt="lihaozhe 选用的个人头像" width="625" height="621" fetchpriority="high"></div>
    <figcaption><span>数学 · 学习 · 探索</span><span aria-hidden="true">01 / PROFILE</span></figcaption>
  </figure>
</section>

<section class="section-block" id="research" aria-labelledby="research-title">
  <div class="section-heading"><div><p class="eyebrow">RESEARCH INTERESTS</p><h2 id="research-title">研究兴趣</h2></div><span class="section-number" aria-hidden="true">01</span></div>
  <div class="interest-grid">
    <article class="interest-card">
      <div class="card-top"><span class="card-index">I.</span><span class="pill">几何与拓扑</span></div>
      <h3>几何拓扑</h3><p class="english-title" lang="en">Geometry &amp; Topology</p>
      <p>围绕几何与拓扑展开学习，记录对概念、结构和证明的理解，以及由此产生的问题。</p>
    </article>
    <article class="interest-card">
      <div class="card-top"><span class="card-index">II.</span><span class="pill">数学与智能</span></div>
      <h3>Math for AI</h3><p class="english-title" lang="en">Mathematics for Artificial Intelligence</p>
      <p>关注人工智能相关的数学，整理学习与论文阅读中的线索，思考数学与 AI 之间的联系。</p>
    </article>
  </div>
</section>

<section class="section-block" id="work" aria-labelledby="work-title">
  <div class="section-heading"><div><p class="eyebrow">PROJECTS &amp; WORK</p><h2 id="work-title">研究与作品</h2></div><span class="section-number" aria-hidden="true">02</span></div>
  {% if site.data.portfolio.projects.size > 0 %}
  <div class="work-list">{% for item in site.data.portfolio.projects %}
    <article class="work-item"><div><p class="eyebrow">{{ item.kind | escape }}</p><h3><a href="{{ item.url | relative_url }}">{{ item.title | escape }} <span aria-hidden="true">↗</span></a></h3><p>{{ item.description | escape }}</p></div></article>
  {% endfor %}</div>
  {% else %}
  <div class="quiet-state"><span class="quiet-mark" aria-hidden="true">↗</span><div><h3>持续探索，逐步积累。</h3><p>可公开的研究材料与个人作品将陆续整理于此。</p></div></div>
  {% endif %}
</section>

<section class="section-block notes-section" id="notes" aria-labelledby="notes-title">
  <div class="section-heading"><div><p class="eyebrow">NOTES &amp; IDEAS</p><h2 id="notes-title">笔记与思考</h2></div><span class="section-number" aria-hidden="true">03</span></div>
  {% if site.data.portfolio.notes.size > 0 %}
  <div class="work-list">{% for item in site.data.portfolio.notes %}
    <article class="work-item"><div><p class="eyebrow">{{ item.kind | escape }}</p><h3><a href="{{ item.url | relative_url }}">{{ item.title | escape }} <span aria-hidden="true">↗</span></a></h3><p>{{ item.description | escape }}</p></div></article>
  {% endfor %}</div>
  {% else %}
  <p class="notes-copy">学习笔记、论文阅读与科研过程中的思考。<br>在理解中记录，在回顾中继续探索。</p>
  {% endif %}
  <div class="topic-tags"><span>几何拓扑</span><span>Math for AI</span><span>科研心得</span></div>
</section>
