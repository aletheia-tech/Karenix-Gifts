---
layout: product
title: Cobalt Twist Plate Rectangle 16 Inch
item-id: cobalt-twist-plate-rectangle-16-inch
image_path: ../../../images/home-decor/cobalt-twist-plate-rectangle-16-inch.jpg
category: home-decor
permalink: /products/home-decor/cobalt-twist-plate-rectangle-16-inch/
description: "Cobalt and navy race across this 16 inch, rectangular plate. Shimmering silver trails behind, with speckles near the bottom of the design. The vibrant colors make a beautiful centerpiece for a dining table, or a wonderful work of art to hang on the wall for an elegant addition to any room. Maintain the beautiful shine of the colors by hand washing with soap and warm water. Our handcrafted Cozenza Glassware is food safe, and lead and cadmium free."
price_usd: 58.50
price_ttd: 395
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