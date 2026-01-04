---
layout: page
title: Projects
permalink: /projects/
description: Research artifacts—codebases, datasets, benchmarks, demos.
nav: true
nav_order: 2
display_categories: []
horizontal: false
---

<div class="projects">

{% assign sorted_projects = site.projects | sort: "importance" %}

<div class="row row-cols-1 row-cols-md-2">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

</div>
