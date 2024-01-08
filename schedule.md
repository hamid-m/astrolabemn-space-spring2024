---
layout: page
title: Schedule
nav_order: 2
description: Listing of tentative course schedule.
---

# Schedule
Below is the course schedule.  This page will be updated as the class progresses.
Assignments are labeled in **BLUE**{: .label .label-blue} and will be checked the following week.
{% for module in site.modules %}
{{ module }}
{% endfor %}
