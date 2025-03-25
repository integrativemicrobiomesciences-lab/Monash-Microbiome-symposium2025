---
title: About
nav:
  order: 1
  tooltip: About, Organising committee, Speakers, Sponsors
---

# Microbiome sciences at Monash University

Mission statement for symposium 

<br/>
<br/>

# {% include icon.html icon="fa-solid fa-users" %}Organising committee

Introduction to our organising committee


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

### Speakers

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html background="images/background.jpg" dark=true %}

### Sponsors

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
