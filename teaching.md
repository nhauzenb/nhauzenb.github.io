---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Teaching at policy institutions
======

{% assign policy_teaching = site.teaching | where: "group", "policy" | sort: "order" %}
{% for post in policy_teaching %}
  {% include archive-single.html %}
{% endfor %}

<br>

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

<br>

Supervision
======

**PhD supervision.** First supervisor of three PhD students:

* Petra Gresó (since 2025).
* Thiago Da Cruz Alves Santos (since 2026).
* Eunice Mwangi (since 2025; first supervisor since July 2026).

**Other supervision.** 1 MRes dissertation, 9 honours dissertations, and 13 MSc dissertations at the University of Strathclyde; 4 MSc dissertations at the Scottish Graduate Programme in Economics. MSc dissertation topics for the current academic year are available on request.

**PhD examination.** External examiner (opponent) for Oliver Snellman (University of Helsinki, 2025); internal examiner for Nick Fritsch (University of Strathclyde and Federal Reserve Bank of Cleveland, 2026).
