---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact


{%
  include button.html
  type="email"
  text="jennie.pouget@camh.ca"
  link="jennie.pouget@camh.ca"
%}
{%
  include button.html
  type="phone"
  text="(416) 535-8501 x30041"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="[https://www.google.com/maps/place/1025+Queen+St+W,+Toronto,+ON+M6J+1H1/@43.6440959,-79.4206487,17z/data=!3m1!4b1!4m6!3m5!1s0x882b357652e44b4d:0xde527c5511424126!8m2!3d43.644092!4d-79.4180738!16s%2Fg%2F11qwskyfqm?entry=ttu&g_ep=EgoyMDI1MTAyMi4wIKXMDSoASAFQAw%3D%3D]"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/painting2.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}
