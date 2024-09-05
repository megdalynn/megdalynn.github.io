---
layout: archive
title: "Work in Progress"
permalink: /wip/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign sorted_wip = site.wip | sort: 'priority' %}
{% for post in sorted_wip %}
  {% include archive-single.html %}
{% endfor %}




<!---
---
layout: archive
title: "Work in Progress"
permalink: /wip/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.wip %}
  {% include archive-single.html %}
{% endfor %}
