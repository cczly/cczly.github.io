---
layout: default
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
---

{% assign home = site.data.home %}

<style>
  .zh-page {
    color: #3f474f;
    font-size: 0.98em;
    line-height: 1.82;
  }

  .zh-page h1,
  .zh-page h2,
  .zh-page h3 {
    color: #1f2933;
    letter-spacing: 0;
  }

  .zh-page a {
    text-underline-offset: 0.18em;
  }

  .zh-intro {
    padding: 0 0 1.35em;
    border-bottom: 1px solid #dce2e8;
  }

  .zh-intro h1 {
    margin: 0 0 0.5em;
    font-size: 1.8em;
    line-height: 1.25;
  }

  .zh-lead {
    color: #2f3740;
    font-size: 1.05em;
  }

  .zh-section {
    padding: 1.45em 0 1.35em;
    border-bottom: 1px solid #e7ebef;
  }

  .zh-admissions {
    margin-top: 1.1em;
    padding-top: 1.1em;
    border-top: 1px solid #dce2e8;
  }

  .zh-admissions__summary {
    margin: 0.2em 0 0.95em;
    color: #65717c;
  }

  .zh-admissions-list {
    display: grid;
    gap: 0.85em;
  }

  .zh-admission-card {
    padding: 0.95em 1em;
    border: 1px solid #dfe5eb;
    border-radius: 8px;
    background: linear-gradient(180deg, #fbfcfe 0%, #f6f9fc 100%);
  }

  .zh-admission-card__meta {
    display: flex;
    align-items: center;
    gap: 0.65em;
    margin-bottom: 0.45em;
  }

  .zh-admission-card__meta strong {
    color: #1d4f8f;
    font-size: 1.02em;
  }

  .zh-status-badge {
    display: inline-block;
    padding: 0.12em 0.52em;
    border-radius: 999px;
    background: #e7f1ff;
    color: #1d4f8f;
    font-size: 0.78em;
    font-weight: 700;
    white-space: nowrap;
  }

  .zh-admission-card p {
    margin: 0;
    color: #2f3740;
  }

  .zh-section__header {
    margin-bottom: 0.8em;
  }

  .zh-section__header h2 {
    margin: 0;
    font-size: 1.28em;
    line-height: 1.35;
  }

  .zh-section__summary {
    margin: -0.15em 0 1em;
    color: #65717c;
  }

  .zh-timeline,
  .zh-awards,
  .publication-list {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .zh-timeline li {
    display: grid;
    grid-template-columns: 5.6em minmax(0, 1fr);
    gap: 0.9em;
    padding: 0.42em 0;
    border-top: 1px dashed #e1e6eb;
  }

  .zh-timeline li:first-child {
    border-top: 0;
  }

  .zh-timeline time,
  .zh-awards strong {
    color: #1d4f8f;
    font-weight: 700;
    white-space: nowrap;
  }

  .zh-awards {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.65em 1.2em;
  }

  .zh-awards li {
    display: grid;
    grid-template-columns: 4em minmax(0, 1fr);
    gap: 0.65em;
    padding: 0.52em 0;
    border-top: 1px dashed #e1e6eb;
  }

  .zh-research-list {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.9em;
  }

  .zh-research-list article {
    padding: 0.85em 0.95em;
    border: 1px solid #dfe5eb;
    border-radius: 6px;
    background: #fafbfc;
  }

  .zh-research-list h3 {
    margin: 0 0 0.35em;
    font-size: 0.98em;
  }

  .zh-research-list p {
    margin: 0;
    color: #56616c;
    font-size: 0.94em;
    line-height: 1.7;
  }

  .publication-list {
    counter-reset: publication;
  }

  .publication-list li {
    position: relative;
    padding: 0.75em 0 0.85em 2.25em;
    border-top: 1px solid #e7ebef;
  }

  .publication-list li::before {
    counter-increment: publication;
    content: counter(publication);
    position: absolute;
    left: 0;
    top: 0.92em;
    width: 1.45em;
    height: 1.45em;
    border-radius: 999px;
    background: #eef3f8;
    color: #365a7d;
    font-size: 0.76em;
    font-weight: 700;
    line-height: 1.45em;
    text-align: center;
  }

  .authors {
    color: #5b6570;
  }

  .pub-badge,
  .pub-link {
    display: inline-block;
    margin: 0 0.28em 0.22em 0;
    padding: 0.12em 0.48em;
    border-radius: 4px;
    font-size: 0.78em;
    font-weight: 700;
    line-height: 1.45;
    white-space: nowrap;
  }

  .pub-badge {
    background-color: #0b2d4d;
    color: #fff;
  }

  .pub-link {
    background-color: #eef0f2;
  }

  .pub-link a {
    color: #3b4cc0;
  }

  @media (max-width: 720px) {
    .zh-awards,
    .zh-research-list {
      display: block;
    }

    .zh-research-list article {
      margin-bottom: 0.75em;
    }

    .publication-list li {
      padding-left: 0;
    }

    .publication-list li::before {
      display: none;
    }
  }
</style>

<div class="zh-page">
  <span class="anchor" id="-about-me"></span>

  <header class="zh-intro">
    <h1>{{ home.profile.zh.name }}</h1>
    {% for paragraph in home.profile.zh.paragraphs %}
      <p{% if forloop.index == 2 %} class="zh-lead"{% endif %}>{{ paragraph }}</p>
    {% endfor %}

    <div class="zh-admissions">
      <span class="anchor" id="-admissions"></span>
      <div class="zh-section__header">
        <h2>{{ home.admissions.title_zh }}</h2>
      </div>
      <p class="zh-admissions__summary">{{ home.admissions.summary_zh }}</p>
      <div class="zh-admissions-list">
        {% for item in home.admissions.items %}
          <article class="zh-admission-card">
            <div class="zh-admission-card__meta">
              <strong>{{ item.year }}</strong>
              <span class="zh-status-badge">{{ item.status_zh }}</span>
            </div>
            <p>{{ item.zh }}</p>
          </article>
        {% endfor %}
      </div>
    </div>
  </header>

  <section class="zh-section" aria-labelledby="news-heading">
    <span class="anchor" id="-news"></span>
    <div class="zh-section__header">
      <h2 id="news-heading">最新动态</h2>
    </div>
    <ol class="zh-timeline">
      {% for item in home.news %}
        <li><time>{{ item.date }}</time><span>{{ item.zh }}</span></li>
      {% endfor %}
    </ol>
  </section>

  <section class="zh-section" aria-labelledby="honors-heading">
    <span class="anchor" id="-honors-and-awards"></span>
    <div class="zh-section__header">
      <h2 id="honors-heading">荣誉奖励</h2>
    </div>
    <ul class="zh-awards">
      {% for item in home.honors %}
        <li><strong>{{ item.year }}</strong><span>{{ item.zh }}</span></li>
      {% endfor %}
    </ul>
  </section>

  <section class="zh-section" aria-labelledby="research-heading">
    <span class="anchor" id="-research-highlights"></span>
    <div class="zh-section__header">
      <h2 id="research-heading">研究方向</h2>
    </div>
    <div class="zh-research-list">
      {% for item in home.research %}
        <article>
          <h3>{{ item.title_zh }}</h3>
          <p>{{ item.desc_zh }}</p>
        </article>
      {% endfor %}
    </div>
  </section>

  <section class="zh-section" aria-labelledby="publications-heading">
    <span class="anchor" id="-publications"></span>
    <div class="zh-section__header">
      <h2 id="publications-heading">代表成果</h2>
    </div>
    <p class="zh-section__summary">以下列出近期代表性成果，完整论文列表与英文主页保持同步。</p>

    <ol class="publication-list">
      {% for paper in home.publications %}
        <li>
          <span class="pub-badge">{{ paper.venue }}</span>
          {% if paper.code_url %}
            <span class="pub-link"><a href="{{ paper.code_url }}">Code</a></span>
          {% endif %}
          <a href="{{ paper.url }}">{{ paper.title }}</a>.
          <span class="authors">{{ paper.authors }}</span>
        </li>
      {% endfor %}
    </ol>
  </section>
</div>
