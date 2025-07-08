---
title: Participate and Location
nav:
  order: 5
  tooltip: Participate and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Participate

Please use the following Google Forms to (1) submit an abstract, and/or (2) register attendance 

{%
  include button.html
  text="Submit an abstract"
  link="https://docs.google.com/forms/d/16bGmc_smLFiCeqRelTzt8UZkinHDQQjzZjtr5oznu_M/edit?ts=67e0b11a"
%}

{%
  include button.html
  text="Register attendance"
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
  image="images/MonashLearningVillage.jpg"
  caption="Learning Village<br/>
  33 Innovation Walk,<br/>
  Monash Univeristy<br/>
  *Image source: ArchitectureAU*"
%}

{% endcapture %}

{% include cols.html col1=col1 %}

{% include section.html dark=true %}
