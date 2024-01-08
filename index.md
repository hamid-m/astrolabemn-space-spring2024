---
layout: home
title: Home
nav_exclude: false
nav_order: 0
permalink: /:path/
seo:
  type: Course
  name: Space Science 
---

# Welcome to Space Science

----
## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Schedule 
Below is the course schedule.  This page will be updated as the class progresses.
Assignments are labeled in **BLUE**{: .label .label-blue} and will be checked the following week.  Optional resources are labled in **YELLOW**{: .label .label-yellow}.
{% for module in site.modules %}
{{ module }}
{% endfor %}
