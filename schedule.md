---
layout: page
title: Daily Schedule
description: The weekly event schedule.
nav_exclude: false
nav_order: 2
---

# Daily Schedule (Updated Each Week)

If the calendar below appears blank, make sure you're signed in to your Berkeley email! 

As an alternative, use <a href="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FLos_Angeles&title=CS10%20Sp23%20Schedule&src=Y19kYmRhYWIyYjdlMDY2MGU3NDMwNTVlNzMyYjAxYTk3MzNmMmM0ZjhiZDFjN2JiMmVlMTk1ODRlMTAwZmIxYjI5QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=Y18yNTFlOWI1MzY3NDQ2MGI2MzI5ZTExMDYzZGZiMDE2ZDAyMmQyODUwYWM0MjY5ODNmMzNiOTU0MWIxMzlkNThhQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=Y18wYjIwN2JmOWRhYzk3ZmY3NjE0MzRlMzRhMjBjYjNjNWRlZjVkOTRkNWEwMmI5MjUzMWE3OTYyYzM3NTVmMDAwQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=Y181N2VkNTIyZjNjMDdmOGM4ZGRhMmY2YjRjNWUxMjk5MWNkNGI1MzA3YmNmN2VlYWE2ODNkMDU0MDliODA1YmJiQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%23C0CA33&color=%23B39DDB&color=%23616161&color=%23F09300">(this link)</a>

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}