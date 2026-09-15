---
layout: archive
title: ""
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

<br>

Supervision
======

**PhD supervision.** Funded studentships are listed under [Research grants]({{ base_path }}/grants/).

**MSc dissertations.** Topics for the current academic year are available on request.
