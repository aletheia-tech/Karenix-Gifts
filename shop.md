---
layout: tailwind
title: Index
permalink: /shop/
---

<!--<div class="flex flex-wrap text-center">
{% assign cookies = site.products | where: "categories", "cookie" %}
{% for product in cookies %}
  <div class="w-1/2 bg-gray-400 h-32"><a href="{{ product.url }}">{{ product.title }}</a></div>
  {% endfor %}
</div>-->
<div class="container bg-gray-100 mx-6 mt-6 mx-auto p-4">
<h1 class="text-center text-xl text-blue-700 tracking-wider" >Customizable Books</h1>
</div>

<div class="flex flex-wrap min-w-0 max-w-full lg:px-16 p-4 justify-evenly">
  {% assign custom-books = site.products | where: "categories", "custom-books" %}
  {% for product in custom-books %}
  <div class="w-64 px-3 bg">
    <div class="bg-white rounded-lg my-4 overflow-hidden border shadow-lg">
      <div>
      <a data-fancybox="gallery" href="{{ product.image_path }}"><img class="h-48 w-full object-cover object-top lozad image-to-load-first" src="{{ product.image_path }}" data-src="{{ product.image_path }}"></a>
      </div>
      <div>
        <div>
          <h3 class="text-sm text-gray-700 -m-2">{{ product.excerpt }}</h3>
        </div>
        <h1 class="font-semibold text-lg m-4 text-gray-900 leading-tight truncate"><a href="{{ product.url }}">{{ product.title }}</a></h1>
        <!--<h2 class="text-xs m-4 text-gray-500 uppercase tracking-wide">{{ product.categories }}</h2>-->
        <h3 class="text-xs text-gray-500 m-4 truncate">{{ product.description }}</h3>
      </div>
    </div>
  </div>
{% endfor %}
</div>

<div class="container mx-auto bg-gray-100 mx-auto my-6 p-4">
<h1 class="text-center text-xl text-blue-700 tracking-wider" >Niks n' Knacks</h1>
</div>

<div class="flex flex-wrap min-w-0 max-w-full lg:px-16 p-4 justify-evenly">
  {% assign niks-n-knacks = site.products | where: "categories", "niks-n-knacks" %}
  {% for product in niks-n-knacks %}
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
        <!--<h2 class="text-xs m-4 text-gray-500 uppercase tracking-wide">{{ product.categories }}</h2>-->
        <h3 class="text-xs text-gray-500 m-4 truncate">{{ product.description }}</h3>
      </div>
    </div>
  </div>
{% endfor %}
</div>

<!--
<div class="max-w-3xl text-3xl text-white bg-gray-500 mx-auto my-16 p-16">
<h1>Cookies</h1>
</div>
{% assign cookies = site.products | where: "categories", "cookie" %}
{% for product in cookies %}
  <div class="px-4">
    <div class="max-w-3xl bg-white rounded-lg mx-auto my-16 p-16">
      <h1 class="text-2xl font-medium mb-2"><a href="{{ product.url }}">{{ product.title }}</a></h1>
      <h2 class="font-medium text-sm text-indigo-400 mb-4 uppercase tracking-wide">{{ product.categories }}</h2>
      {{ product.description }}
      {{ product.content }}
    </div>
  </div>
{% endfor %}
-->

<!--
<div class="max-w-3xl text-3xl text-white bg-gray-500 rounded-lg mx-auto my-16 p-16">
<h1>All Products</h1>
</div>
{% for product in site.products %}
  <div class="px-4">
    <div class="max-w-3xl bg-white rounded-lg mx-auto my-16 p-16">
      <h1 class="text-2xl font-medium mb-2"><a href="{{ product.url }}">{{ product.title }}</a></h1>
      <h2 class="font-medium text-sm text-indigo-400 mb-4 uppercase tracking-wide">Responsive Navbar</h2>
      {{ product.description }}
    </div>
  </div>
{% endfor %}
-->