---
title: Thesis
nav:
  order: 1
  tooltip: Thesis proposals
---

# {% include icon.html icon="fa-solid fa-terminal" %}Thesis Proposals

Here we have some proposals for thesis and internships to be done in our laboratory, all centered around autonomous systems.

{% capture col1 %}
# ChAoS
{% include list.html component="card" data="thesis" filter="group == 'chaos'" %}
{% endcapture %}
{% capture col2 %}
# Computer Vision
{% include list.html component="card" data="thesis" filter="group == 'vision'" %}
{% endcapture %}
{% capture col3 %}
# Drone Development
{% include list.html component="card" data="thesis" filter="group == 'drone'" %}
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
  col3=col3
%}