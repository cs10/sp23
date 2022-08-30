---
layout: page
title: Daily Schedule
description: The weekly event schedule.
nav_exclude: false
nav_order: 2
---

# Daily Schedule (Updated Each Week)

If the calendar below appears blank, make sure you're signed in to your Berkeley email! 

As an alternative, use <a href="https://natomasunified.org/kb/3937-2/">(this link)</a>

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
