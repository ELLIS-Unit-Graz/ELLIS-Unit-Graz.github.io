---
title: Team
nav:
  order: 4
  tooltip: Our Members
---

# {% include icon.html icon="fa-solid fa-users" %}Our Members

{% include list.html data="members" component="portrait" filter="role == 'director'" %} 
{% include list.html data="members" component="portrait" filter="role == 'fellow'" %}
{% include list.html data="members" component="portrait" filter="role == 'scholar'" %}
{% include list.html data="members" component="portrait" filter="role == 'member'" %}
{% include list.html data="members" component="portrait" filter="role == 'coordinator'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-handshake"%} Partners

Our researchers are actively involved in various consortia, projects, and collaborations. 

{% include list.html component="card" data="projects" filter="!group" style="small" %}
