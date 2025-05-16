---
title: About
nav:
  order: 1
  tooltip: About, Organising committee, Speakers, Sponsors
---

# Microbiome sciences at Monash University

The *Microbiome at Monash Symposium* is a one-day event dedicated to bringing together reserchers from across the university who share an interest in microbiome sciences. Its mission is to foster interdisciplinary dialogue, showcase ongoing research, and catalyse new collaborations that advance microbiome-related discovery and innovation at Monash. 

<br/>
<br/>

# {% include icon.html icon="fa-solid fa-users" %}Organising committee

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

# Keynote Speakers

{% include section.html %}

{% capture content %}

{% include figure.html image="images/MvO.jpg" caption="Professor Madeleine van Oppen **FAA** <br/> University of Melbourne <br/> Australian Institute of Marine Sciences <br/> Australian Academy of Science"%}
{% include figure.html image="images/Marsland_Ben.jpg" caption="Professor Benjamin Marsland <br/> Monash University <br/> Department of Immunology and Pathology" %}



{% include section.html background="images/background.jpg" dark=true %}

# Inivted Speakers

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" caption="invited speaker"%}
{% include figure.html image="images/photo.jpg" caption="invited speaker" %}


{% endcapture %}

{% include grid.html style="square" content=content %}
