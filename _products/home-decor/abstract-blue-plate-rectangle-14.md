---
layout: product
title: Abstract Blue Plate 14 Inch Rectangle
item-id: abstract-blue-plate-rectangle-14
image_path: ../../../images/home-decor/abstract-blue-plate-rectangle-14.jpg
category: home-decor
permalink: /products/home-decor/abstract-blue-plate-rectangle-14/
description: "Blue and silver splashes against a powerful gradient on this modern piece of glassware. The creases of the lips fold in asymmetrically for an avant-garde twist on the 14 inch, rectangular dish, and offer the light interesting angles to catch the shining colors. This piece makes a beautiful accent to any modern decor. Hang on a wall, or place on a table or shelf for a sophisticated addition to any room. Cozenza glassware is food safe, and free of any lead or cadmium. Maintain the beautiful shine of the colors by hand washing with soap and warm water. Our handcrafted cozenza glassware is food safe, and lead and cadmium free."
price_usd: 55.54
price_ttd: 375
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