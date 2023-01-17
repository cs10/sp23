---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

# **CS 10: The Beauty and Joy of Computing**
{: .mb-2 }
UC Berkeley, Spring 2023
{: .mb-2 .fs-6 .text-grey-dk-100 }

{{ site.description }}
{: .mb-2 .fs-5 }

**Instructor:** Teaching Professor Dan Garcia
{: .fs-4 }

<br/>

<i>Check out this video on what CS 10 is all about and how we leave an impact!!!</i>

{% include youtube.html id='oG1OItm4JyU' %}

<br/>

<div class="d-flex">  
  <div class="flex-justify-start" style="flex-grow: 1">
  {% if site.announcements %}
    {{ site.announcements.last }}
  {% endif %}
  </div>
  <div class="float-right">
    <img src="/sp22/assets/images/alonzo.png" alt="Alonzo, the CS10 Mascot" />
  </div>
</div>
<div style="flex-grow: 0">
  <a href="{{ site.baseurl }}/announcements" class="btn btn-outline">Previous Announcemnts</a>
</div>

## CS10 Calendar

{% include_relative calendar.md %}
