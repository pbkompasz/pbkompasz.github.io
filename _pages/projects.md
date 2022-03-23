---
layout: content
title: projects
permalink: /projects/
---

| PROJECT NAME  | TYPE | DESCRIPTION | LAUNCH DATA | CURRENT STATUS | 
| :----: | :----: | :----: | :----: | :----: | 
| [{{site.projects[0].title}}]({{site.projects[0].url}}) | Chrome extension / node.js library | Chrome extension that let's you mark blablabla | 04-2022 | development |

{% for project in site.projects %}
<!-- [{{project.title}}]({{project.url}}) -->
| {{project.title}} | {{ project.type}} | {{ project.description}} | {{ project.releaseDate}} | {{ project.status}}|
{% endfor %}

