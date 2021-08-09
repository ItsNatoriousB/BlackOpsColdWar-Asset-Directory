---
date: 2020-11-22 18:21:00
layout: data_test
datatable: true
title: BOCW Camos
subtitle: "xModel names for camos"
description: >-
  "xModel list for camo names"
image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1606095662/headers/Multiplayer_Screenshot_07_ckes6n.jpg
optimized_image: >- 
  https://res.cloudinary.com/natoriousb/image/upload/v1606095662/headers/Multiplayer_Screenshot_07_ckes6n.jpg
featured_image: >-
  https://res.cloudinary.com/natoriousb/image/upload/v1606095662/headers/Multiplayer_Screenshot_07_ckes6n.jpg
category: assets
tags:
  - camo
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

<p class="image-gallery">
{% for image in page.images %}
        <img src="thumbs/{{ image.name }}" alt="{{ image.name }}" title="{{ image.name }}" />
        <span>{{ filename }}</span>
{% endfor %}
</p>