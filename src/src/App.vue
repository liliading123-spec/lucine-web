<template>
  <div class="font-sans text-gray-800">

    <!-- Header -->
    <header class="flex justify-between items-center p-6 shadow">
      <div class="text-xl font-bold">Lucine Floor</div>
      <nav class="space-x-6 text-sm">
        <a href="#products">Products</a>
        <a href="#future">Future</a>
        <a href="#resources">Resources</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <!-- Hero -->
    <section class="text-center py-20 bg-gray-50">
      <h1 class="text-4xl font-bold mb-4">
        Flexible Quartz Flooring for Africa & Southeast Asia
      </h1>

      <p class="mb-6">
        1-3mm Ultra Thin | Lower Shipping Cost | No Cracking
      </p>

      <div class="space-x-4">
        <a :href="whatsappLink" target="_blank"
          class="bg-green-600 text-white px-6 py-3">
          WhatsApp Now
        </a>

        <button class="border px-6 py-3">
          Get Price List
        </button>
      </div>
    </section>

    <!-- Advantage -->
    <section class="py-16 px-6 max-w-5xl mx-auto">
      <h2 class="text-2xl font-bold mb-6">
        Why Flexible Quartz Flooring Wins
      </h2>

      <h3>✔ No cracking during installation</h3>
      <h3>✔ Works in high temperature markets</h3>
      <h3>✔ Save 30% shipping cost</h3>
    </section>

    <!-- Future -->
    <section id="future" class="py-16 px-6">
      <h2 class="text-2xl font-bold">
        New Production Line (Q3 2026)
      </h2>
      <p>USA & EU standard flooring in development</p>
    </section>

    <!-- Resources -->
    <section id="resources" class="py-16 px-6">
      <h2 class="text-2xl font-bold mb-6">
        Buyer Guides
      </h2>

      <p>SPC vs Quartz Flooring</p>
      <p>Import Cost Guide</p>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-16 px-6">
      <h2 class="text-2xl font-bold mb-6">
        Contact Factory Direct
      </h2>

      <a :href="whatsappLink" target="_blank"
        class="bg-green-600 text-white px-6 py-3">
        Chat on WhatsApp
      </a>
    </section>

    <!-- Floating WhatsApp -->
    <a :href="whatsappLink"
       target="_blank"
       class="fixed bottom-6 right-6 bg-green-500 text-white px-4 py-3 rounded-full shadow-lg">
       WhatsApp
    </a>

  </div>
</template>

<script setup>
const whatsappLink = "https://wa.me/8615898737651?text=Hello%20I%20am%20interested%20in%20your%20flooring"
</script>
