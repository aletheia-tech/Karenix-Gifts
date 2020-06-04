---
layout: product
title: Giraffe Bank
item-id: giraffe-bank
image_path: ../../../images/novelty-items/giraffe-bank.jpg
category: novelty-items
permalink: /products/novelty-items/giraffe-bank/
description: "Perfect gift, unless you decided to keep it for yourself! The ceramic giraffe is not only super cute put also helps you save money. I believe that is what they call amazing! Material: glazed ceramic."
price_usd: 26.81
price_ttd: 183.00
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