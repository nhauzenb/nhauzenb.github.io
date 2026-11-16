---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Current teaching activities
======

Scottish Graduate Programme in Economics (SGPE)
------

{% assign courses = site.teaching | where: "group", "sgpe" | sort: "order" %}
{% for post in courses %}
  {% include archive-single.html %}
{% endfor %}

MSc in Economics, Data Science and AI (EDSAI)
------

I am Director of [this programme](https://www.strath.ac.uk/courses/postgraduatetaught/economicsdatascienceartificialintelligence/) and helped shape its curriculum. I led the development of the three modules below, on which I also lecture.

{% assign courses = site.teaching | where: "group", "edsai" | sort: "order" %}
{% for post in courses %}
  {% include archive-single.html %}
{% endfor %}

Other teaching at Strathclyde
------

{% assign courses = site.teaching | where: "group", "strath" | sort: "order" %}
{% for post in courses %}
  {% include archive-single.html %}
{% endfor %}

<br>

Past teaching activities
======

{% for post in site.pastteaching reversed %}
  {% include archive-single.html %}
{% endfor %}
