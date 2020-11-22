---
date: 2020-11-20 12:00:00
layout: post
title: BOCW Character Hashes
subtitle: "xModel names for characters assets"
description: >-
  "xModel list for character assets"
image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605874498/headers/Multiplayer_Screenshot_03_yyp5ry.jpg
optimized_image: >- 
  https://res.cloudinary.com/natoriousb/image/upload/v1605874498/headers/Multiplayer_Screenshot_03_yyp5ry.jpg
featured_image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1605874498/headers/Multiplayer_Screenshot_03_yyp5ry.jpg
category: assets
tags:
  - xmodel
  - hashes
  - names
  - characters
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
  {% for row in site.data.character-hashes %}
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