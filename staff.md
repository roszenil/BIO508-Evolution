---
layout: page
title: Instructor
nav_order: 4
description: A listing of all instructors
---


# Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}



