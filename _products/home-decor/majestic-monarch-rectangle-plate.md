---
layout: product
title: Majestic Monarch Rectangle Plate
item-id: majestic-monarch-rectangle-plate
image_path: ../../../images/home-decor/majestic-monarch-rectangle-plate.jpg
category: home-decor
permalink: /products/home-decor/majestic-monarch-rectangle-plate/
description: "Butterflies are nature's angels reminding us what a gift it is to be alive. Bring a calming feel to your decor with the peaceful beauty of our Majestic Monarch Plate. This plate features rich lavender blooms with shimmery accents throughout each piece which are all hand-painted. Plate is 16 inches high. Our handcrafted cozenza glassware is food safe, and lead and cadmium free."
price_usd: 49.08
price_ttd: 335.00
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