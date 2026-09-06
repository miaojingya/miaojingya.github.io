---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="profile-blocks profile-blocks--single">
{% for section in site.data.profile_sections.sections %}
  {% if section.enabled %}
  <section class="profile-block" id="{{ section.id }}">
    <h2>{{ section.title }}</h2>

{% if section.body %}
  <div class="profile-block__body">{{ section.body | markdownify }}</div>
{% endif %}

{% if section.items %}
<ul class="profile-timeline">
  {% for item in section.items %}
  <li>
    <strong class="profile-timeline__degree">{{ item.title }}</strong>
    <span class="profile-timeline__meta">
      {{ item.organization }}, {{ item.city }}
      <span class="profile-timeline__diamond" aria-hidden="true">◆</span>{{ item.date }}
    </span>
    {% if item.detail %}
      <span class="profile-timeline__detail">{{ item.detail }}</span>
    {% endif %}
  </li>
  {% endfor %}
</ul>
{% endif %}

{% if section.tags %}
  <ul class="profile-tags">
    {% for tag in section.tags %}<li>{{ tag }}</li>{% endfor %}
  </ul>
{% endif %}

  </section>
  {% endif %}
{% endfor %}
</div>
<br>
<p class="profile-cta"><a class="btn btn--primary" href="{{ '/cv/' | relative_url }}">View full curriculum vitae</a></p>
