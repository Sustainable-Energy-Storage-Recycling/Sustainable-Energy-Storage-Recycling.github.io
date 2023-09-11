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
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
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
