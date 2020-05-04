---
layout: tailwind
title: Contact & Support
permalink: /contact/
---

<div class="px-4">
  <div class="max-w-3xl bg-white rounded-lg mx-auto my-16 p-16">
    <h1 class="text-2xl font-medium mb-2">{{ page.title }}</h1>
    <h2 class="font-medium text-sm text-indigo-400 mb-4 uppercase tracking-wide">Karenix Gift & Card Shoppe #51-53 Long
      Circular Road St James</h2>
    <!-- AJAX submissions cannot work with reCAPTCHA enabled -->
    <form class="w-full max-w" id="my-form" action="https://formspree.io/mleprwdd" method="POST">
      <div class="flex flex-wrap -mx-3 mb-6">
        <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
          <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">
            First Name
          </label>
          <input
            class="appearance-none block w-full bg-gray-200 text-gray-700 border rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white"
            type="text" placeholder="Jane" name="first-name" required>
          <p class="text-gray-600 text-xs italic">Please fill out this field.</p>
        </div>
        <div class="w-full md:w-1/2 px-3">
          <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">
            Last Name
          </label>
          <input
            class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
            id="grid-last-name" type="text" name="last-name" placeholder="Doe" required>
        </div>
      </div>
      <div class="flex flex-wrap -mx-3 mb-6">
        <div class="w-full px-3">
          <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">
            Email
          </label>
          <input
            class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
            type="email" name="email" placeholder="me@domain.com" required>
          <p class="text-gray-600 text-xs italic">Please provide a valid email address.</p>
        </div>
      </div>
      <div class="flex flex-wrap -mx-3 mb-6">
        <div class="w-full px-3">
          <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">
            Message
          </label>
          <textarea
            class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
            name="message" rows="10" cols="30" required></textarea>
          <p class="text-gray-600 text-xs italic">Your message goes here.</p>
        </div>
      </div>
      <p class="text-red-400 text-xs italic pb-3">Please note: You will be redirected briefly in order to send this
        email.</p>
      <button id="my-form-button"
        class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline">Send</button>
      <p id="my-form-status"></p>
    </form>
    <p class="py-4 text-gray-700">
      Karenix Gifts cares about our customers and their ideas on the store. We would love to hear from you.<br><br> If you have
      comments, suggestions or product questions please fill out the form above, give us a call or message on <strong>WhatsApp via +1 (868) 680-5474</strong>. Email us
      at <strong>karenixtt@gmail.com</strong>.
    </p>
  </div>
</div>