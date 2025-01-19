---
layout: default
title: Courses
has_children: true
nav_order: 2
---

# Large Language Models

{: .mb-2 }
University of Tehran, Spring 2025
{: .mb-0 .fs-6 .text-grey-dk-000 }

[Elearn](https://elearn.ut.ac.ir){:target="\_blank" .btn .btn-ed .mr-1 }


<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{: .highlight }

> Lectures will be webcast at: [https://www.aparat.com/nlp_group/live](https://www.aparat.com/nlp_group/live){:target="\_blank"}.
