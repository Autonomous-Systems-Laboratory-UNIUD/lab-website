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







{% include section.html background="images/background.jpg" dark=true %}

Our group also features two specialized teams:
- Vision: Dealing with computer visions applications to UAVs and robotic domains.
- ChAoS (Choreographies of Autonomous Systems): Researching formal control and coordination tecniques for fleets of robots.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
