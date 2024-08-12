---
title: People
nav:
  order: 6
---

# {% include icon.html icon="fa-solid fa-users" %}Team

#### Faculty (Principal Investigator)
{% include list_pi.html data="members" component="portrait_pi" filters="role: pi" %}
#### Graduate Students
{% include list_students.html data="members" component="portrait_students" filters="role: grad" %}
#### Undergraduate Students
{% include list_students.html data="members" component="portrait_students" filters="role: under" %}
#### Visiting Scholar/Students
{% include list_students.html data="members" component="portrait_students" filters="role: visiting" %}