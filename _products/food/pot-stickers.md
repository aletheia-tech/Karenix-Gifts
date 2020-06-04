---
layout: product
title: Pot Stickers
image_path: ../../../images/food/.jpg
category: food
permalink: /products/food/pot-stickers/
description: 
price_usd: 5.00
price_ttd: 35
excerpt_separator: <!--more-->
---

<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold my-2 py-2 px-4 rounded w-full snipcart-add-item" 
data-item-id="pot-stickers" 
data-item-price="{{page.price_usd}}"
data-item-url="https://www.karenix.com/food"
data-item-description="{{ page.description }}"
data-item-image="{{page.image_path}}"
data-item-name="{{page.title}}">
${{page.price_usd}} USD or ${{page.price_ttd}} TTD
</button>

<!--more-->

<div class="flex flex-wrap">
  <div class="w-64 p-4 h-auto">
    <a data-fancybox="gallery" href="{{ page.image_path }}"><img src="{{ page.image_path }}"></a>
  </div>
  <div class="sm:flex-1">
    <p class="p-4 text-gray-700">
      <strong>
      </strong>
      <br><br>
    </p>
  </div>
</div>
