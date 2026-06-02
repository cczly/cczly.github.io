---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% assign home = site.data.home %}

<span class="anchor" id="-about-me"></span>

{% for paragraph in home.profile.en.paragraphs %}
{{ paragraph }}

{% endfor %}

<span class="anchor" id="-news"></span>

# News

{% for item in home.news %}
- *{{ item.date }}*: {{ item.en }}
{% endfor %}

<span class="anchor" id="-honors-and-awards"></span>

# Honors and Awards

{% for item in home.honors %}
- **{{ item.year }}**: {{ item.en }}
{% endfor %}

<span class="anchor" id="-research-highlights"></span>

# Research Highlights

{% for item in home.research %}
- **{{ item.title_en }}**: {{ item.desc_en }}
{% endfor %}

<span class="anchor" id="-publications"></span>

# Publications

(*, Corresponding Author)

<ul class="publication-list publication-list--en">
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
</ul>

# Acknowledgement

Thanks for this convenient [template](https://github.com/RayeRen/acad-homepage.github.io).
