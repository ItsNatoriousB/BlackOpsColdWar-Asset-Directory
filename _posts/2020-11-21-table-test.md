---
date: 2020-11-21 18:11:00
layout: weapon-post
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

<div class="datatable-begin compact"></div>
<table style="width: 100%; text-align: center; margin-left: auto; margin-right: auto;" border="none">
  {% for row in site.data.weapons-list %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

   {% tablerow pair in row %}
   {{ pair[1] }}
   {% endtablerow %}
  {% endfor %}
</table>
<div class="datatable-end"></div>