---
---

# ELLIS Unit Graz

Welcome to the website of the ELLIS Unit Graz. This website is currently under construction and will be filled within the coming months. 

{% include section.html %}

{% capture text %}

In our unit we work on a broad range of cutting-edge fundamental research topics to strenghten the development of high-level European AI.

{%
  include button.html
  link="research"
  text="Explore our expertise"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Reading group

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Reading Group"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our Unit consist of high-level researchers in the field of AI.

{%
  include button.html
  link="team"
  text="Meet the members of our Unit"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
