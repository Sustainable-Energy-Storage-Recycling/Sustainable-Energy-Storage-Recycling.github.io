---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a dedicated group of professionals united by a common mission to drive innovation, efficiency, and excellence in energy-related processes within our organization. 
Our team plays a pivotal role in shaping the digital landscape of our company, fostering collaboration, and driving sustainable practices in the energy sector.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: Principal Intergator" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

We are a dedicated group of professionals united by a common mission to drive innovation, efficiency, and excellence in energy-related processes within our organization. 
Our team plays a pivotal role in shaping the digital landscape of our company, fostering collaboration, and driving sustainable practices in the energy sector.

{% include section.html %}

{% capture content %}

{% include figure.html image="profile/01sai-gu.jpg" %}
{% include figure.html image="profile/02zeyuan-meng.jpg" %}
{% include figure.html image="profile/03junxian-wang.jpg" %}
{% include figure.html image="profile/04liang-xu.jpg" %}
{% include figure.html image="profile/05haotian-ma.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
