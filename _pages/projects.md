---
layout: content
title: Projects
permalink: /projects/
---

Projects I worked on/currently working on
- [Tets project]({{ "/test-project" | prepend: site.baseurl }})

{{}}

{% for project in site.projects %}
    {{project.title}}
{% endfor %}

