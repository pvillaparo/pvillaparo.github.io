---
layout: single
title: "Miscellaneous"
permalink: /miscellaneous/
excerpt: "Side projects outside my research that I enjoy building and sharing."
author_profile: true
---

{% include base_path %}

Not everything I build ends up in a paper. This is where I keep side projects that I find fun and useful, from tools that helped me learn something new to small data explorations about places I care about.

<nav class="misc-grid" aria-label="Miscellaneous projects">
  {% for project in site.data.miscellaneous %}
    {% if project.url contains '://' %}
      {% assign project_href = project.url %}
    {% else %}
      {% assign project_href = project.url | prepend: base_path %}
    {% endif %}
    <a class="misc-card" href="{{ project_href }}">
      {% if project.icon %}
        <img class="misc-card__icon" src="{{ base_path }}{{ project.icon }}" alt="" aria-hidden="true">
      {% endif %}
      <span class="misc-card__body">
        <span class="misc-card__title">{{ project.title }}</span>
        {% if project.language %}<span class="misc-card__tag">{{ project.language }}</span>{% endif %}
        <span class="misc-card__text">{{ project.description }}</span>
        <span class="misc-card__more">Open <span aria-hidden="true">→</span></span>
      </span>
    </a>
  {% endfor %}
</nav>
