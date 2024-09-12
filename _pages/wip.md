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
Fisher, Megdalynn, Ari Ne'eman, Kosali Simon. "Resident Intent to Return to the Community: Implications of Facility Quality and Ownership on Transition Patterns."



<!---
{% include base_path %}

{% for post in site.prep | sort: 'priority' %}
  {% include archive-single-talk.html %}
{% endfor %}
