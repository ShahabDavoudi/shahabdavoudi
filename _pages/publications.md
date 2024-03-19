| Authors          | Title  |Status         |
| --------         | ------ | ----------------- |
| Shahab Davoudi Kashani,Omid Tavakoli   | Hydrogen Production from Cigarette Filters Using Catalytic Hydrothermal Gasification Technology   | In preparation    |
| Shahab Davoudi Kashani, Mostafa Ghiami, Omid Tavakoli   | Simulation of Hydrogen Production from Distillery Wastewater via Hydrothermal Gasification: Optimization with Machine Learning   | In preparation    |
| Shahab Davoudi Kashani, Mohammad Ali Nazem , Omid Tavakoli     | Refinery Waste to Bio-Oil: Catalytic Hydrothermal Liquefaction of Oily Sludge   | Submitted to journal    |
| Negar Kazemi , Shahab Davoudi Kashani, Omid Tavakoli    | Mechanistic Investigation of Biofuel Production from Algal Biomass and Organic Waste via Nano-Catalytic Pyrolysis Process   | In preparation    |



---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
