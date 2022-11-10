---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


Research Projects (PhD)
======
{% include base_path %}

{% for post in site.projects.projects_research reversed %}
  {% include archive-single.html %}
{% endfor %}


Academic Projects
======
{% include base_path %}

{% for post in site.projects.projects_acad reversed %}
  {% include archive-single.html %}
{% endfor %}