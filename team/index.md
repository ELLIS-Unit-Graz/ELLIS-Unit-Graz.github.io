---
title: Team
nav:
  order: 4
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

{% include figure.html image="images/TUGraz_logo.png" %}
{% include figure.html image="images/GraML_logo.jpg" %}
{% include figure.html image="images/BilAI_logo.png" %}

{% endcapture %}

{% include grid.html style="square" content=content %}


