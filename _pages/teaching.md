---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Current teaching activities
======

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>

Past teaching activities
======

{% for post in site.pastteaching reversed %}
  {% include archive-single.html %}
{% endfor %}
