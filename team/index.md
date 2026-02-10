---
title: Team
nav:
  order: 4
  tooltip: Our Members
---

# {% include icon.html icon="fa-solid fa-users" %}Our Members

{% include list.html data="members" component="portrait" filter="role == 'director' and group != 'alum'" %} 
{% include list.html data="members" component="portrait" filter="role == 'fellow' and role != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'scholar' and role != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'member' and role != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'coordinator' and group != 'alum'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-handshake"%} Projects & Partners

Our researchers are actively involved in various consortia, projects, and collaborations. 

{% include list.html component="card" data="projects" filter="!group" style="small" %}
