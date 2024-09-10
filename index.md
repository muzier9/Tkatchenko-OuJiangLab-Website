---
title: Home
carousels:
  - images: 
    - image: ./images/team/group_outside.jpg
    - image: ./images/team/group_outside.jpg
    - image: ./images/team/group_outside.jpg
left-carousels:
  - images: 
    - image: ./images/team/group_outside.jpg
    - image: ./images/team/Research2.png
---

# muzier9OuJiangLab


{% include section.html size="full" %}

{% include carousel-news.html size="carousel-news" height="40" unit="%" duration="10" number="1" %}

{% include section.html %}

## Highlights

{% capture text %}

By using patient data, mice model, and retinal organoids, our research aims to identify,
assess, and predict genetic variations which can lead to Mendelian and complex visual disorders.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team/Research1.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We believe that anyone around the world should be able to use and extend our work. 
We push to make software, tools, datasets, etc. that are freely available.

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
  image="images/research.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a team of enthusiastic researchers and we strive to build an inclusive environment for research,
and recognize the value of diversity in the process of discovery.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team/group_outside.jpg"
  link="team"
  title="Our Team"
  text=text
%}
