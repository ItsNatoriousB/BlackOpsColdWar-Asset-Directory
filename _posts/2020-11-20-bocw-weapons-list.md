---
date: 2020-11-20 21:00:00
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

<div><h2>SMGS</h2></div>

1. MP5 - **smg_standard**
1. AK-74u - **smg_heavy**
1. KSP 45 - **smg_burst**
1. Milano 821 - **handling_beta**
1. Bullfrog - **smg_capacity**

<div><h2>Tactical rifles</h2></div>

1. Type 63 - **tr_damagesemi**
1. M16 - **tr_longburst**
1. AUG - **tr_powerburst**
1. DMR 14 - **tr_precisionsemi**

<div><h2>LMGS</h2></div> 

1. M60 - **lmg_slowfire**
1. RPD - **lmg_light**
1. Stoner 63 - **lmg_accurate**

<div><h2>Pistols</h2></div>

1. 1911 - **pistol_semiauto**
1. Magnum -  **pistol_revolver**
1. Diamatti -  **pistol_burst**

<div><h2>Launchers</h2></div>

1. Cigma 2 - **launcher_standard**
1. RPG-7 - **launcher_freefire**

<div><h2>Melee</h2></div>

1. Knife - **knife_combat_american**

<div><h2>Special</h2></div>

1. M79 - **grenade_launcher**

<div><h2>Shotguns</h2></div>

1. Hauer 77 - **shotgun_pump**
1. Gallo SA12 - **shotgun_semiauto**