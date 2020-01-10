---
layout: page
title: Projects
permalink: /projects/
---

### Personal Projects
Few opensource/public projects that I have contributed to recently.

{% for project in site.projects %}

#### {{ project.title }} <sup><a class="project-link" href="{{ project.project_url}}"><i class="fas fa-external-link-alt"></i></a>project</sup> {% if project.demo_url %} <sup><a class="project-link" href="{{ project.demo_url }}"><i class="fas fa-external-link-alt"></i></a>demo</sup> {% endif %}

> {{ project.description }}

{% endfor %}

### Opensource contributions

- [Mono Project - .Net Runtime on Linux](https://github.com/mono/mono/search?q=sureshkumar&unscoped_q=sureshkumar)<sup><a class="project-link" href="{{ project.project_url}}"><i class="fas fa-external-link-alt"></i></a></sup> 2004-2005
- [Turnpike - IPSec VPN plugins](https://code.google.com/archive/p/turnpike/)<sup><a class="project-link" href="{{ project.project_url}}"><i class="fas fa-external-link-alt"></i></a></sup> 2005-2007
