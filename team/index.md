---
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

{% include figure.html image="images/MvO_04.jpg" caption="[Professor Madeleine van Oppen **FAA**](https://www.aims.gov.au/about/our-people/prof-madeleine-van-oppen) <br/> Australian Institute of Marine Sciences <br/> School of BioSciences, the University of Melbourne<br/> Madeleine van Oppen is a world-leading marine molecular ecologist recognised for pioneering the field of assisted evolution of corals, a transformative approach aimed at enhancing coral resilience to climate change-driven heatwaves and bleaching events. Her research focuses on microbial symbioses, coral adaptation, and reef restoration, with innovations in bioengineering technqiues that accelerate coral acclimatisation and adaptation. Van Oppen's work has been pivotal in shaping global coral conservation efforts and is widely used by research institutions worldwide. Her research has led to over 290 peer-reviewed articles, books and book chpaters."%}
{% include figure.html image="images/Marsland_Ben.jpg" caption="[Professor Benjamin Marsland](https://research.monash.edu/en/persons/benjamin-marsland) <br/> Monash University <br/> Department of Immunology and Pathology" %}


{% endcapture %}

{% include grid.html style="center" columns=2 content=content %}


{% include section.html background="images/background.jpg" dark=true %}

# Inivted Speakers

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" caption="invited speaker"%}
{% include figure.html image="images/photo.jpg" caption="invited speaker" %}


{% endcapture %}

{% include grid.html style="center" columns=2 content=content %}
