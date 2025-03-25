---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please contact one of our committee members with questions

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/19+Ancora+Imparo+Wy,+Clayton+VIC+3168/@-37.9139139,145.129986,17z/data=!3m1!4b1!4m6!3m5!1s0x6ad66acc2f07062d:0xb3d0e2a877a17c63!8m2!3d-37.9139139!4d145.1325609!16s%2Fg%2F11sxvxfwyx?authuser=1&entry=ttu&g_ep=EgoyMDI1MDMxOS4yIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
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
