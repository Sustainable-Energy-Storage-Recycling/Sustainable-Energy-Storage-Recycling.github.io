---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a dedicated group of professionals united by a common mission to drive innovation, efficiency, and excellence in energy-related processes within our organization. 
Our team plays a pivotal role in shaping the digital landscape of our organization, fostering collaboration, and driving sustainable practices in the energy sectors.


{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}<p></p>
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}


{% capture content %}

{% endcapture %}


{% include grid.html style="square" content=content %}


