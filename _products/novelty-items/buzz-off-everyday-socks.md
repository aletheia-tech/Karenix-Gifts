---
layout: product
title: Buzz Off Everyday Socks
item-id: buzz-off-everyday-socks
image_path: ../../../images/novelty-items/buzz-off-everyday-socks.jpg
category: [novelty-items, socks]
permalink: /products/novelty-items/buzz-off-everyday-socks/
description: Our Buzz Off socks feature adorable bumble bees flying on a bright pink sky with yellow and black joints.
price_usd: 7.41
price_ttd: 50
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
      <br><br>
      Made especially for our passive aggressive friends ;)
      <br><br>
      Each style comes in two sizes: Big Feet (Women's 10 - 12.5, Men's 8.5 - 13) and Small Feet (Women's 5.5 - 9.5, Men's 5 -
      8).
      <br><br>
      Machine wash in cold water. Tumble dry. Do not bleach. Or you can just give it to your mom.
      <br><br>
      Made of 75% cotton, 20% polyamide and 5% elastane.
    </p>
  </div>
</div>