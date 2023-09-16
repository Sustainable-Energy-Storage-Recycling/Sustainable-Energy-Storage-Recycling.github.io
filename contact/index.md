---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For more details,please contact [Mr.Haotian Ma](https://github.com/TSdreamer) for more information.

{%
  include button.html
  type="email"
  text="haotianteemo@outlook.com"
  link="haotianteemo@outlook.com"
%}
{%
  include button.html
  type="phone"
  text="(+44) 7404729404"
  link="(+44) 7404729404"
%}
{%
  include button.html
  type="address"
  text="our address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/University+of+Warwick/@52.3792557,-1.5640507,17z/data=!4m14!1m7!3m6!1s0x48774ac696d53ee5:0xaa928d75708b2b54!2sUniversity+of+Warwick!8m2!3d52.3792525!4d-1.5614704!16zL20vMGdsNmY!3m5!1s0x48774ac696d53ee5:0xaa928d75708b2b54!8m2!3d52.3792525!4d-1.5614704!16zL20vMGdsNmY?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/applied mathmatics.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/chemical engineering.png"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}
