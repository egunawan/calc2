---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

Welcome to {{site.data.course.number}}: {{site.data.course.name}}, this {{site.data.course.term}}!

PLEASE REFRESH THE PAGE AT EACH VISIT!

# Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}
