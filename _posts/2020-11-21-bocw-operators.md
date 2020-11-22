---
date: 2020-11-21 21:00:00
layout: post
title: BOCW Operators
subtitle: "xModel names for Operator aassets"
description: >-
  "xModel List for Operator assets"
image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1606014365/headers/Multiplayer_Screenshot_11_mih8fh.jpg
optimized_image: >- 
  https://res.cloudinary.com/natoriousb/image/upload/v1606014365/headers/Multiplayer_Screenshot_11_mih8fh.jpg
featured_image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1606014365/headers/Multiplayer_Screenshot_11_mih8fh.jpg
category: assets
tags:
  - names
  - operators
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
<table class="zmb-table row-border stripe">
  {% for row in site.data.operators %}
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