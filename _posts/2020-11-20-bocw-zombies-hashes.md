---
date: 2020-11-20 12:00:00
layout: post
title: BOCW Zombie Hashes
subtitle: "xModel names for zombie assets"
description: >-
  "xModel list for zombie assets"
image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605873548/headers/Zombies_Screenshot_03_llvhdc.jpg
optimized_image: >- 
  https://res.cloudinary.com/natoriousb/image/upload/v1605873548/headers/Zombies_Screenshot_03_llvhdc.jpg
featured_image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605873548/headers/Zombies_Screenshot_03_llvhdc.jpg
category: assets
tags:
  - xmodel
  - hashes
  - names
  - zombies
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

<div class="datatable-begin"></div>
<table>
  {% for row in site.data.zombies_hashes %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {%- endfor -%}
    </tr>
    {% endif %}

   {% tablerow pair in row %}
   {{ pair[1] }}
   {% endtablerow %}
  {%- endfor -%}
</table>
<div class="datatable-end"></div>