<template>
  <main>
    <section class="text-gray-600 body-font">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-wrap w-full mb-20">
          <div class="lg:w-1/2 w-full mb-6 lg:mb-0">
            <h1 class="title">Geplante Reisen </h1>
            <h2 class="subtitle">Regional und international</h2>
          </div>
          <p class="lg:w-1/2 w-full leading-relaxed text-gray-500">
            Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical gentrify,
            subway tile poke farm-to-table. Franzen you probably haven't heard of them man
            bun deep jianbing selfies heirloom prism food truck ugh squid celiac
            humblebrag.
          </p>
        </div>
        <TripList />
        <TripList />

        <div class="flex justify-center py-24">
          <nuxt-link
            to="/archiv"
            class="inline-flex items-center bg-gray-900 text-gray-200 border-0 py-1 px-3 focus:outline-none hover:bg-gray-800 hover:text-gray-100 rounded text-base"
          >
            Archiv
            <svg
              fill="none"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-4 h-4 ml-1"
              viewBox="0 0 24 24"
            >
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </nuxt-link>
        </div>

      </div>
    </section>
  </main>
</template>
