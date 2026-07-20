---
layout: page
permalink: /teaching/
title: teaching
description: Courses I have taught at TUM
nav: true
nav_order: 6
---

{% for course in site.courses %}
{% if course.nav %}
<a href="{{ course.url | relative_url }}">{{ course.title }}</a>
{% endif %}
{% endfor %}

<div class="courses">
  {% assign sorted_courses = site.courses | sort: "importance" %}
  {% for course in sorted_courses %}
    <div class="course-item">
      <h3>
        <a href="{{ course.url | relative_url }}">{{ course.title }}</a>
      </h3>
      <p class="course-description">{{ course.description }}</p>
    </div>
  {% endfor %}
</div>
