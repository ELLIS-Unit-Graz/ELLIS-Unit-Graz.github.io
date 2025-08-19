---
title: Team
nav:
  order: 1
  tooltip: Our Members
---

# {% include icon.html icon="fa-solid fa-users" %}Our Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'director'" %}

{% include list.html data="members" component="portrait" filter="role == 'Fellow'" %}

{% include list.html data="members" component="portrait" filter="role == 'Scholar'" %}

{% include list.html data="members" component="portrait" filter="role == 'Member'" %}

{% include list.html data="members" component="portrait" filter="role == 'coordinator'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
