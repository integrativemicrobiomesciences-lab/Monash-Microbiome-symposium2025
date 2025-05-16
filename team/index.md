er---
title: About
nav:
  order: 1
  tooltip: About, Organising committee, Speakers, Sponsors
---

# Microbiome sciences at Monash University

The *Microbiome at Monash Symposium* is a one-day event dedicated to bringing together reserchers from across the university who share an interest in microbiome sciences. Its mission is to showcase ongoing research and foster interdisciplinary dialogue, catalysing new collaborations that will strengthen Monash's leadership in microbiome discovery and innovation now and into the future. 

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

{% include figure.html image="images/MvO.jpg" caption="[Professor Madeleine van Oppen **FAA**](https://www.aims.gov.au/about/our-people/prof-madeleine-van-oppen) <br/> University of Melbourne <br/> Australian Institute of Marine Sciences <br/> Australian Academy of Science"%}
{% include figure.html image="images/Marsland_Ben.jpg" caption="[Professor Benjamin Marsland](https://research.monash.edu/en/persons/benjamin-marsland) <br/> Monash University <br/> Department of Immunology and Pathology" %}


{% endcapture %}

{% include grid.html style="square" content=content %}


{% include section.html background="images/background.jpg" dark=true %}

# Inivted Speakers

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" caption="invited speaker"%}
{% include figure.html image="images/photo.jpg" caption="invited speaker" %}


{% endcapture %}

{% include grid.html style="center" columns=2 content=content %}
