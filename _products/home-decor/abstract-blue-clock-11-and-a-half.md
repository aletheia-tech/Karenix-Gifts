---
layout: product
title: Abstract Blue 11 1/2 Clock
item-id: abstract-blue-clock-11-and-a-half
image_path: ../../../images/home-decor/abstract-blue-clock-11-and-a-half.jpg
category: home-decor
permalink: /products/home-decor/abstract-blue-clock-11-and-a-half/
description: "Beautiful tones of blue speckle a light blue to navy gradient in the background of this intricate, hand-painted Clock. Silver hands bring out the lighter colors of the gradient that stretch to 11 1/2 inch tall on this modern, hand-painted decoration. Perfect with any modern Decor, place this Clock on a mantle or end table for an avant-garde way to tell time. Clock is 11 1/2 inches tall. Requires 1 - AA battery (not included). Our handcrafted Cozenza Glassware is food safe, and lead and cadmium free."
price_usd: 38.51
price_ttd: 260
excerpt_separator: <!--more-->
---

<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold my-2 py-2 px-4 w-full snipcart-add-item" 
data-item-id="{{ page.item-id }}" 
data-item-price="{{page.price_usd}}"
data-item-url="{{ site.url }}/{{ page.category }}"
data-item-description="{{ page.description }}"
data-item-image="{{ page.image_path }}"
data-item-name="{{ page.title }}"
data-item-categories="{{ page.category }}">
${{ page.price_usd }} USD or ${{ page.price_ttd }} TTD
</button>

<!--more-->
<div class="flex flex-wrap">
  <div class="w-64 p-4 h-auto">
    <a data-fancybox="gallery" href="{{ page.image_path }}"><img src="{{ page.image_path }}"></a>
  </div>
  <div class="sm:flex-1">
    <p class="p-4 text-gray-700">
      {{ page.description }}
    </p>
  </div>
</div>