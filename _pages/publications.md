---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% include base_path %}

<div class="pub-filter" role="group" aria-label="Filter by theme">
  <span class="pub-filter__label">Show:</span>
  <button type="button" class="pub-filter__btn is-active" data-theme="all">All</button>
  {% for t in site.data.themes %}<button type="button" class="pub-filter__btn" data-theme="{{ t[0] }}">{{ t[1] }}</button>{% endfor %}
</div>

Working papers
======

{% for post in site.wps reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>

Publications in refereed journals
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>

Book chapters and invited discussions
======

{% for post in site.book reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>

Publications in institutional journals
======

{% for post in site.institutional reversed %}
  {% include archive-single.html %}
{% endfor %}
