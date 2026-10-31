---
layout: single
title: Projects
permalink: /projects/
---

A selection of things I've built. Check my [GitHub](https://github.com/{{ site.github_username }}) for everything else.

{% for project in site.data.projects %}
## {{ project.name }}

{{ project.description }}

**Stack:** {{ project.stack | join: ", " }}

{% if project.demo != "" or project.source != "" -%}
{% if project.demo != "" %}[Live Demo]({{ project.demo }}){% endif %}{% if project.demo != "" and project.source != "" %} · {% endif %}{% if project.source != "" %}[Source]({{ project.source }}){% endif %}
{% endif %}
{% unless forloop.last %}
---
{% endunless %}
{% endfor %}
