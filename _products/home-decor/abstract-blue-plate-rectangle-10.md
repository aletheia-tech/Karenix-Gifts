---
layout: product
title: Abstract Blue Plate 10 Inch Rectangle
item-id: abstract-blue-plate-rectangle-10
image_path: ../../../images/home-decor/abstract-blue-plate-rectangle-10.jpg
category: home-decor
permalink: /products/home-decor/abstract-blue-plate-rectangle-10/
description: "Vibrant shades of blue and silver splash onto a gradient of light blue to navy on this beautiful, rectangular dish. The creases for the lips are slightly askew, a modern twist on this 10 inch glassware, and a wonderful focal piece for any contemporary Decor. Cozenza Glassware is food safe, and free of any lead or cadmium. Maintain the beautiful shine of the colors by hand washing with soap and warm water. Our handcrafted Cozenza Glassware is food safe, and lead and cadmium free."
price_usd: 35.55
price_ttd: 240
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