---
layout: home
title: Just the Class
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Just the Class
---

## WHO AM I?

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}



