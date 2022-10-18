<template>
  <section class="bg-gray-50 pb-12">
    <div class="container mx-auto flex">
      <div
        class="mr-auto min-h-96 flex justify-center items-center flex-1 shrink-0 bg-gray-100 overflow-hidden shadow-lg rounded-md relative py-16 md:py-20 xl:py-48"
      >
        <!-- image - start -->
        <img
          src="https://www.architekturinform.com/media/filer_public_thumbnails/filer_public/9c/9b/9c9bcd9c-af99-4dfc-ad6b-98fcd0bb3a31/a_nyc_3_brooklyn_view.jpg__616x347_q95_crop-False_upscale-True.jpg"
          loading="lazy"
          alt="architekturINFORM"
          class="w-full h-full object-cover object-center absolute inset-0 my-0"
        />
        <!-- image - end -->

        <!-- overlay - start -->
        <div class="bg-gray-500 mix-blend-multiply absolute inset-0"></div>
        <!-- overlay - end -->

        <!-- text start -->
        <div class="sm:max-w-xl lg:max-w-6xl flex flex-col items-center relative p-4">
          <p class="text-gray-200 text-lg sm:text-xl text-center mb-4 md:mb-8">
            Architektur entdecken und erleben
          </p>
          <h1
            class="text-white text-4xl sm:text-5xl md:text-6xl font-bold text-center mb-8 md:mb-12"
          >
            Regionale und internationale Architekturreisen
          </h1>

          <div class="w-full flex flex-col sm:flex-row sm:justify-center gap-4">
            <nuxt-link
              to="/reisen"
              class="inline-block bg-gray-200 hover:bg-gray-300 focus-visible:ring ring-indigo-300 text-gray-500 active:text-gray-700 text-sm md:text-base font-semibold text-center rounded-lg outline-none transition duration-100 px-8 py-3"
            >
              Reiseübersicht
            </nuxt-link>

            <nuxt-link
              to="/infos"
              class="inline-block bg-gray-200 hover:bg-gray-300 focus-visible:ring ring-indigo-300 text-gray-500 active:text-gray-700 text-sm md:text-base font-semibold text-center rounded-lg outline-none transition duration-100 px-8 py-3"
            >
              Individuelle Touren
            </nuxt-link>
          </div>
        </div>
        <!-- text end -->
      </div>
    </div>
  </section>
</template>
