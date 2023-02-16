---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 10
---

# Staff
### Add 'berkeley.edu' to the end of all emails.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

## Head Teaching Assistants

{% assign staff = site.staffers | where: 'role', 'Head TA' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div>

## Teaching Assistants

{% assign staff = site.staffers | where: 'role', 'TA' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div>


## Readers

{% assign readers = site.staffers | where: 'role', 'Reader' %}
<div class="role">
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>


## Academic Interns (AI's)

{% assign ai = site.staffers | where: 'role', 'AI' %}
<div class="role">
  {% for staffer in ai %}
    {{ staffer }}
  {% endfor %}
</div>
