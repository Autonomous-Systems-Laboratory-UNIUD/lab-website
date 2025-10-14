---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'full-professor'" %}
{% include list.html data="members" component="portrait" filter="role == 'associate-professor'" %}
{% include list.html data="members" component="portrait" filter="role == 'assistant-professor'" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'fellow'" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'master'" %}
{% include list.html data="members" component="portrait" filter="role == 'bachelor'" %}







{% include section.html background="images/chaos_background.svg" dark=true %}

# ChAoS
The Choreographies of Autonomous Systems (ChAoS) team works on researching innovative and effective ways to coordinate swarms of autonomous systems. Our work ranges from modelling, to the definition of formal languages to the verification of their properties.

{% include section.html background="images/chaos_background.svg" dark=true %}

{% include section.html %}

# Vision

The Vision teams implements and research new ways to combine autonomous systems and computer vision, with a focus on multispectral images
and aerial drones.

{% capture content %}

{% include figure.html image="images/night_ir.png" %}
{% include figure.html image="images/late_fusion_ir.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
