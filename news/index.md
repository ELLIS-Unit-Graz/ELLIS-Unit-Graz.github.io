---
title: News
nav:
  order: 1
  tooltip: 
---

# News from the ELLIS Unit Graz

{% capture text %}

Workshop at ELLIS UNConference 

{%
  include button.html
  link="research"
  text="Learn more about our research topics"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/ELLIS-Society-Photo-50.jpg"
  link="research"
  title="Workshop at ELLIS Unconference"
  text=text
%}

{% capture text %}

This reading group aims to help onboard young scientists interested in the topic of efficient ML and offers researchers at all levels a platform for an open dialog to foster collaboration, and stay up-to-date with rapid developments in the field. We welcome and discuss fresh research findings published as a pre-print or recently presented at research venues. 

{%
  include button.html
  link="projects"
  text="Check out the website of the reading group"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/readinggroup.png"
  link="projects"
  title="Efficient ML Reading Group"
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
