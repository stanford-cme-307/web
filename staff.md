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
Find your instructors after class, in office hours, or by booking an office hours slot [with Madeleine](https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ37cqkJAC5Z_f8dJjHOSb9LjG5kK_FN4iPxoGInZtjZL5uwttVHjmL2ktbkTGBpHilyXEPSqXI9) or [Dan](https://calendar.app.google/dNQUdv3wDxemqKZy6) if your question requires privacy.
* We use the [Ed platform](https://edstem.org/us/courses/105466) to manage online course questions and discussion.
Longer or more mathematically involved questions, or debugging requests, are more appropriate for office hours.
* Grades will be posted on [Gradescope](https://www.gradescope.com/courses/1387345) and should be discussed only real-time, not by email or on Ed.
* Direct email to instructors should be used to submit letters from OAE
or to schedule a meeting with an instructor if the bookable office hours slots for [Madeleine](https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ37cqkJAC5Z_f8dJjHOSb9LjG5kK_FN4iPxoGInZtjZL5uwttVHjmL2ktbkTGBpHilyXEPSqXI9) and [Dan](https://calendar.app.google/dNQUdv3wDxemqKZy6) don't fit your schedule.

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
