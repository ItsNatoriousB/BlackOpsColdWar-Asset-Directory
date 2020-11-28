---
date: 2020-11-21 18:11:00
layout: table_test
datatable: true
title: BOCW Weapons
subtitle: "Names for wapons"
description: >-
  "A list for gun names"
image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605925653/headers/Multiplayer_Screenshot_12_jct9fr.jpg
optimized_image: >- 
  https://res.cloudinary.com/natoriousb/image/upload/v1605925653/headers/Multiplayer_Screenshot_12_jct9fr.jpg
featured_image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605925653/headers/Multiplayer_Screenshot_12_jct9fr.jpg
category: assets
tags:
  - weapons
  - hashes
  - names
author: itsnatorioub
paginate: true
credits:
  - Scobalula
  - DTZxPorter
  - Activision
  - Infinity Ward
  - Raven
  - High Moon
version: v1.0.0.0
game: "Call of Duty: Black Ops Cold War (2020)"
type: custom_content
---

  <!-- Testing Code -->
{% for camo in site.data.camos %}
  {{ camo | inspect }} => ["layout", "table_test"]
{% endfor %}
  <!-- Loop Start -->
{% for camo in site.data.camos %}
  <!-- Camo Name Start-->
  {% for pair in camos %}
    {% if forloop.first %}
<span class="camo-name">{{ pair[1] }}</span>
    {%- endif -%}
  {%- endfor -%}
  <!-- Camo Name End -->
{%- endfor -%}
  <!-- Loop End -->