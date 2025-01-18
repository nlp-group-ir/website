---
layout: page
title: Weekly Schedule
parent: Large Language Models
description: The weekly class schedule.
---

# Weekly Schedule
{% for attribute in site.schedules[0] %}
  {{ attribute[0] }}: {{ attribute[1] }}<br>
{% endfor %}

{{ site.schedules }}
