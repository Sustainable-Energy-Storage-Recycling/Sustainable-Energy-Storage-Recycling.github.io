---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a dedicated group of professionals united by a common mission to drive innovation, efficiency, and excellence in energy-related processes within our organization. 
Our team plays a pivotal role in shaping the digital landscape of our company, fostering collaboration, and driving sustainable practices in the energy sector.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="haotian-ma.jpeg" %}
{% include figure.html image="liang-xu.jpg" %}
{% include figure.html image="sai-gu.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
