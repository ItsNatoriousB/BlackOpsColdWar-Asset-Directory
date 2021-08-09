---
date: 2020-11-19 12:00:00
layout: post
title: BOCW Xmodel Hashes
subtitle: "xModel Names for game assets"
description: >-
  "xModel list for game assets"
image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605874656/headers/Campaign_Screenshot_02_eqbsxp.jpg
optimized_image: >- 
  https://res.cloudinary.com/natoriousb/image/upload/v1605874656/headers/Campaign_Screenshot_02_eqbsxp.jpg
featured_image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605874656/headers/Campaign_Screenshot_02_eqbsxp.jpg
category: assets
tags:
  - xmodel
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

<div class="datatable-begin row-border stripe"></div>
<table class="weapons-table display">
  {% for row in site.data.xmodel %}
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