---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% include base_path %}


Publications in refereed journals
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

======
======

Publications in institutional journals
======

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
