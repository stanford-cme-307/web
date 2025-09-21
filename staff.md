---
layout: page
title: Contact
description: A listing of all the course staff members.
---

<!-- # Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`. -->

## Course communication 

* The best way to communicate is real-time, in person or on Zoom. 
<!-- Real-time meetings are more efficient, more effective, and more fun. -->
Find your instructors after class, in office hours, or by [booking an office hours slot](https://calendar.app.google/eeHciuuD1mdrCYQy7) if your question requires privacy.
* We use the [Ed platform](https://edstem.org/us/courses/87386/discussion/) to manage offine course questions and discussion. 
Longer or more mathematically involved questions, or debugging requests, are more appropriate for office hours.
* Grades will be posted on Gradescope and should be discussed only real-time, not by email or on Ed.
* Direct email to instructors should be used to submit letters from OAE
or to schedule a meeting with an instructor if our open office hours times (below) and [bookable office hours slots](https://calendar.app.google/eeHciuuD1mdrCYQy7) don't fit your schedule.

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
