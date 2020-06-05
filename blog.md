---
layout: tailwind
title: Blog
permalink: /blog/
excerpt_separator: <!--more-->
---

<!--<input type="text" id="input" v-model="message">-->

<!--
{% for post in site.posts %}
  <div class="px-4">
    <div class="max-w-3xl bg-white rounded-lg mx-auto my-16 p-16">
      <h1 class="mb-2 text-2xl font-medium text-gray-900"><a href="{{ post.url }}">{{ post.title }}</a></h1>
      <h2 class="mb-4 font-medium text-sm text-gray-500 uppercase tracking-wide">{{ post.date }}</h2>
      <p class="text-gray-700">{{ post.description }}</p>
    </div>
  </div>
{% endfor %}
-->

<section class="text-gray-700 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-wrap -m-4">
    {% for post in site.posts %}
      <div class="p-4 md:w-1/3">
        <div class="h-full border-2 border-gray-200 rounded-lg overflow-hidden">
          <img class="lg:h-48 md:h-36 w-full object-cover object-center" src="{{ post.image_path }}" alt="blog">
          <div class="p-6">
            <h2 class="tracking-widest text-xs title-font font-medium text-gray-500 mb-1 capitalize">{{ post.categories }}</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">{{ post.title }}</h1>
            <p class="leading-relaxed mb-3">{{ post.description }}</p>
            <div class="flex items-center flex-wrap ">
              <a class="text-indigo-500 inline-flex items-center md:mb-2 lg:mb-0" href="{{ post.url }}">Learn More
                <svg class="w-4 h-4 ml-2" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round"> <path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
              </a>
            </div>
          </div>
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
</section>