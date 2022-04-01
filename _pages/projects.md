---
layout: content
title: projects
permalink: /projects/
---

| PROJECT NAME  | TYPE | DESCRIPTION | LAUNCH DATA | CURRENT STATUS | 
| :----: | :----: | :----: | :----: | :----: | 
{% for project in site.projects -%}
| [{{project.title}}](https://raw.githubusercontent.com/mkchoi212/paper-jekyll-theme/master/_posts/2016-08-15-style-test.md) | {{ project.type}} | {{ project.description}} | {{ project.releaseDate}} | {{ project.status}} |
{% endfor -%}
{:.mbtablestyle}

