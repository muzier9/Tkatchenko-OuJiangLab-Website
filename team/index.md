---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is made up of a highly engaged and collaborative team of researchers. We recognize that diverse teams do better research.
We foster an environment where team members are treated equally, and where we respect and admire our differences.
The team includes faculty, postdocs, students at all levels and staff.

Andrei V. Tkatchenko Group

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Computer Group

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Computer Group

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}


{% include section.html background="images/banner.jpg" size="wide"%}

### We’re always on the lookout for new and unique perspectives. 
{:.center}

{% include button.html type="external" link="Join%20us" text="Join the Team" tooltip="Join us"%} 
{:.center}
