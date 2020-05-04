---
layout: tailwind
title: Home
permalink: 
excerpt_separator: <!--more-->
---

{% for post in site.posts %}
  <div class="px-4">
    <div class="max-w-3xl bg-white rounded-lg mx-auto my-16 p-16">
      <h1 class="text-2xl font-medium mb-2 text-gray-900"><a href="{{ post.url }}">{{ post.title }}</a></h1>
      <h2 class="font-medium text-sm text-indigo-400 mb-4 uppercase tracking-wide">{{ post.date }}</h2>
      <p class="text-gray-700">{{ post.description }}</p>
    </div>
  </div>
{% endfor %}