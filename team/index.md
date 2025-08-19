---
title: Team
nav:
  order: 1
  tooltip: Members of the ELLIS Unit Graz
---

# {% include icon.html icon="fa-solid fa-users" %}Members of the ELLIS Unit Graz

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'director'" %}

{% include list.html data="members" component="portrait" filter="role == 'Fellow'" %}

{% include list.html data="members" component="portrait" filter="role == 'Scholar'" %}

{% include list.html data="members" component="portrait" filter="role == 'Member'" %}

{% include list.html data="members" component="portrait" filter="role == 'coordinator'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
