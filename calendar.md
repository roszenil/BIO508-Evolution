---
layout: page
title: Weekly work
description: Listing of weekly readings, lectures, and practicals
---

# What are we doing each week?

{% for module in site.modules %}
{{ module }}
{% endfor %}
