---
layout: content
title: projects
permalink: /projects/
---

| PROJECT NAME  | TYPE | DESCRIPTION | LAUNCH DATA | CURRENT STATUS | 
| :----: | :----: | :----: | :----: | :----: | 
{% for project in site.projects -%}
| {{project.title}} | {{ project.type}} | {{ project.description}} | {{ project.releaseDate}} | {{ project.status}} |
{% endfor -%}
{:.mbtablestyle}

