---
layout: archive
title: "Work in Progress"
permalink: /wip/
author_profile: true
---
# Working Papers
{% include base_path %}

{% for post in site.wip | sort: 'priority' %}
  {% include archive-single.html %}
{% endfor %}

# In Preparation
{% include base_path %}

{% for post in site.prep | sort: 'priority' %}
  {% include archive-single.html %}
{% endfor %}
