---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

contact

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps"
  link="https://www.google.com/maps?client=firefox-b-d&channel=entpr&um=1&ie=UTF-8&fb=1&gl=de&sa=X&geocode=KbXt0c6FSm5HMS3YVeXsd9F_&daddr=Inffeldgasse+25D,+8010+Graz,+Austria"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
