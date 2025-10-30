---
title: Team
nav:
  order: 4
  tooltip: Our Members
---

# {% include icon.html icon="fa-solid fa-users" %}Our Members

{% include section.html %}

{% include list.html component="card" data="members" filter="group == 'director'" style="small" %}

{% include list.html data="members" component="portrait" filter="role == 'director'" %}

{% include list.html data="members" component="portrait" filter="role == 'Fellow'" %}

{% include list.html data="members" component="portrait" filter="role == 'Scholar'" %}

{% include list.html data="members" component="portrait" filter="role == 'Member'" %}

{% include list.html data="members" component="portrait" filter="role == 'coordinator'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

## Projects & Partners

Our researchers are actively involved in various consortia, projects, and collaborations. 

{% include list.html component="card" data="projects" filter="!group" style="small" %}{% 

{% include grid.html style="square" content=content %}

