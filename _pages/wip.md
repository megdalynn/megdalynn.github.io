---
layout: archive
title: "Work in Progress"
permalink: /wip/
author_profile: true
---

{% include base_path %}

{% for post in site.wip | sort: 'priority' %}
  {% include archive-single.html %}
{% endfor %}


