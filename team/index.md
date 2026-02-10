---
title: Team
nav:
  order: 3
  tooltip: Our Members
---

# {% include icon.html icon="fa-solid fa-users" %}Our Members

{% include list.html data="members" component="portrait" filter="role == 'director'" %} 
{% include list.html data="members" component="portrait" filter="role == 'fellow'" %}
{% include list.html data="members" component="portrait" filter="role == 'scholar'" %}
{% include list.html data="members" component="portrait" filter="role == 'member'" %}
{% include list.html data="members" component="portrait" filter="role == 'coordinator'" %}

{% include section.html %}
