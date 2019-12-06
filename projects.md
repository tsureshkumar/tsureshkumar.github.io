---
layout: page
title: Projects
permalink: /projects/
---
{% for project in site.projects %}
#### {{ project.title }}  <sup><a class="project-link" href="{{ project.project_url}}"><i class="fas fa-external-link-alt"></i></a></sup>

> {{ project.description }}

{% endfor %}
