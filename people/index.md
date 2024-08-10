---
title: People
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

#### Faculty (Principal Investigator)
{% include list_pi.html data="members" component="portrait" filters="role: pi" %}
#### Graduate Students
{% include list_students.html data="members" component="portrait" filters="role: grad" %}
#### Undergraduate Students
{% include list_students.html data="members" component="portrait" filters="role: undergrad" %}
#### Visiting Scholar/Students
{% include list_students.html data="members" component="portrait" filters="role: visiting" %}