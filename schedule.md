---
layout: page
title: Weekly Schedule
description: The weekly event schedule.
---

# Weekly Schedule

Section 011: Tuesday 11-11:50 AM (in-person, see classroom on One)

Section 012: Tuesday 11:15-12:05 PM (in-person, see classroom on One)

Section 013: Monday 5:30-6:20 PM (in-person, see classroom on One)

Section 014: Monday 5-5:50 PM (in-person, see classroom on One)

Section 015: Tuesday 1-1:50 PM (in-person, see classroom on One)

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
