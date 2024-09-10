---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

[Our lab](http://www.ojlab.cn/) is located at 999 Jinshi Road, Yongzhong Street, Longwan District, Wenzhou City.

{:.center}

<!--
{%


  include button.html


  type="email"


  text="jane@smith.com"


  link="jane@smith.com"


%}


{%


  include button.html


  type="phone"


  text="(555) 867-5309"


  link="+1-555-867-5309"


%}


{%


  include button.html


  type="address"


  tooltip="Our location on Google Maps for easy navigation"


  link="https://www.google.com/maps"


%}
-->

{% include section.html %}

{% capture col1 %}

##### Office 5013
##### Systems genetics and pharmacogenomics of myopia Group 
##### Ocular diseases and Visual Function Recovery Research Cluster
##### OuJiang Lab
##### Yongzhong Street, Longwan District, Wenzhou
##### China

{%
  include button.html
  type="email"
  text="andreiv.tkatchenko@ojlab.ac.cn"
  tooltip="Email"
  link="andreiv.tkatchenko@ojlab.ac.cn"
%}
{:.center}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/OuJiangLab.webp"
  caption="Oujiang Laboratory Qihang Building"
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
