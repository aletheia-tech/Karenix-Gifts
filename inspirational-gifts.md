---
layout: tailwind
title: Inspirational Gifts
permalink: /inspirational-gifts/
---

<div class="container mx-6 mt-6 p-8 mx-auto">
<h1 class="text-center text-2xl text-blue-700 tracking-wider">Inspirational Gifts</h1>
</div>

<div class="flex flex-wrap min-w-0 max-w-full lg:px-16 p-4 justify-evenly">
  {% assign inspirational-gifts = site.products | where: "categories", "inspirational-gifts" %}
  {% for product in inspirational-gifts %}
  <div class="w-64 px-3 bg">
    <div class="bg-white rounded-lg my-4 overflow-hidden border shadow-lg">
      <div>
      <a data-fancybox="gallery" href="{{ product.image_path }}"><img class="h-48 w-full object-cover object-top" src="{{ product.image_path }}"></a>
      </div>
      <div>
        <div>
          <h3 class="text-sm text-gray-700 -m-2">{{ product.excerpt }}</h3>
        </div>
        <h1 class="font-semibold text-lg m-4 text-gray-900 leading-tight truncate"><a href="{{ product.url }}">{{ product.title }}</a></h1>
        <h3 class="text-xs text-gray-500 m-4 truncate">{{ product.description }}</h3>
      </div>
    </div>
  </div>
{% endfor %}
</div>