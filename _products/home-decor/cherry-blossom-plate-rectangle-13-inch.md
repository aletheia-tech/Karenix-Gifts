---
layout: product
title: Cherry Blossom Plate Rectangle 13 Inch
item-id: cherry-blossom-plate-rectangle-13-inch
image_path: ../../../images/home-decor/cherry-blossom-plate-rectangle-13-inch.jpg
category: home-decor
permalink: /products/home-decor/cherry-blossom-plate-rectangle-13-inch/
description: "The beautiful colors of spring sway in the breeze on this 13 inch rectangular, rippled plate. Shimmering Cherry Blossoms leave trails of pinks and whites on a speckled, green background on this beautiful, hand-painted piece. Maintain the beautiful shine of the colors by hand washing with soap and warm water. Our handcrafted Cozenza Glassware is food safe, and lead and cadmium free."
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