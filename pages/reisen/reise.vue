<template>
  <main>
    <section class="text-gray-600 body-font">
      <div class="container px-5 pt-24 pb-8 mx-auto">
        <div class="flex flex-wrap w-full">
          <div class="lg:w-1/2 w-full mb-6 lg:mb-0">
            <h1 class="title">New York & Chicago</h1>
            <h2 class="subtitle">5. – 15 November 2022</h2>
          </div>
          <div class="lg:w-1/2 w-full leading-relaxed text-gray-500">
            <p>
              Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical gentrify,
              subway tile poke farm-to-table. Franzen you probably haven't heard of them
              man bun deep jianbing selfies heirloom prism food truck ugh squid celiac
              humblebrag.
            </p>
          </div>
        </div>
      </div>

      <div class="container mx-auto">
        <img
          src="https://www.architekturinform.com/media/filer_public_thumbnails/filer_public/9c/9b/9c9bcd9c-af99-4dfc-ad6b-98fcd0bb3a31/a_nyc_3_brooklyn_view.jpg__616x347_q95_crop-False_upscale-True.jpg"
          loading="lazy"
          alt="architekturINFORM"
          class="w-full rounded-md mt-0"
        />
      </div>

      <div class="container mx-auto max-w-4xl py-16">
        <div class="lg:w-4/5">
          <h3>Programm</h3>
          <div>
            <p>
              pulsiert mit kreativer Energie: Die bekannte Skyline befindet sich in
              ständiger Veränderung, neue Quartiere entwickeln sich auf ehemals
              unzugänglichem Land, und internationale Architekten-Superstars hinterlassen
              ihre Spuren in jeder Ecke der Stadt. Schlanke "Supertall"-Wolkenkratzer, das
              weltweit höchste Passivhaus, temporäre Kunstinstallationen und neue
              innovative Grünflächen konkurrieren um die Aufmerksamkeit der
              Öffentlichkeit, und ganze Stadtteile verändern sich mit atemberaubender
              Geschwindigkeit. Im vergangenen Jahrzehnt sind in New York City eine
              bemerkenswerte Anzahl neuer Gebäude von einigen der bekanntesten Architekten
              aus der ganzen Welt entstanden: Adjaye, BIG, Foster, Fuksas, Hadid, Herzog &
              de Meuron, Nouvel, OMA, Piano und SANAA haben sich zu ihren amerikanischen
              Kollegen Diller Scofdio + Renfro, Gehry, Holl, Meier, Morphosis, Selldorf,
              SHOP und SOM gesellt und neue faszinierende Anlaufpunkte geschaffen. Von
              Museen, Galerien, Hotels, Restaurants, Bars und Geschäften bis hin zu ihren
              Wohn- und Bürohäusern und öffentlichen Räumen - in New York hat eine neue
              Ära der Architektur begonnen.
            </p>
            <p>
              Gemeinsam werden wir auf Stadtspaziergängen und einer Radtour New Yorks
              neueste Gebäude und einige wichtige Ikonen der Architekturgeschichte des 20.
              Jahrhunderts erkunden sowie interessante Nachbarschaften, neue faszinierende
              Parks und bedeutende Kunstinstallationen entdecken.
            </p>
            <p>
              Außerdem steht ein Tagesausflug zum Yale Campus nach New Haven mit Bauten
              u.a. von Louis Kahn, Eero Saarinen, Paul Rudolph, Marcel Breuer und SOM auf
              dem Programm.
            </p>
          </div>
        </div>
      </div>

    <section class="container mx-auto max-w-4xl py-16">
      <h3>Anfragen</h3>
      <div>
        <div class="flex flex-wrap -m-2">
          <div class="p-2 w-1/2">
            <div class="relative">
              <label for="name" class="leading-7 text-sm text-gray-600">Name</label>
              <input
                type="text"
                id="name"
                name="name"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-gray-500 focus:bg-white focus:ring-2 focus:ring-gray-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
          </div>
          <div class="p-2 w-1/2">
            <div class="relative">
              <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
              <input
                type="email"
                id="email"
                name="email"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-gray-500 focus:bg-white focus:ring-2 focus:ring-gray-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
          </div>
          <div class="p-2 w-full">
            <div class="relative">
              <label for="message" class="leading-7 text-sm text-gray-600">Nachricht</label>
              <textarea
                id="message"
                name="message"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-gray-500 focus:bg-white focus:ring-2 focus:ring-gray-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"
              ></textarea>
            </div>
          </div>
          <div class="p-2 w-full">
            <button
              class="flex mx-auto text-white bg-gray-800 border-0 py-2 px-8 focus:outline-none hover:bg-gray-800 rounded text-lg"
            >
              Anfragen
            </button>
          </div>
        </div>
      </div>
    </section>

      <div class="container mx-auto py-24">
          <h3>Weitere Reisen</h3>
          <TripList />
      </div>
    </section>
  </main>
</template>
