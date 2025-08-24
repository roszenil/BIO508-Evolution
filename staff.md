---
layout: page
title: Instructor
description: A listing of all instructors
---


# Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}



