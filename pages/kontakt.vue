<template>
  <main>
    <HeroContact />

    <section class="container mx-auto max-w-4xl py-16">
      <div class="lg:w-2/3">
        <h2 class="title">Mag. phil. Brigitte Raos</h2>
        <h3 class="subtitle">Geschäftsleitung</h3>
        <p>
          Geschäftsleiterin des Kunstraums Engländerbau, Vaduz/FL Studium der
          Kunstgeschichte an der Universität Innsbruck Akad. geprüfte Tourismusmanagerin.
          Vorstandsmitglied des A&K Fachvereins SIA, Schweiz.
        </p>
      </div>
    </section>

    <section class="container mx-auto max-w-4xl py-16">
      <div class="flex gap-8 mb-16">
        <div class="lg:w-2/3">
          <h3>Referenzauszug</h3>
          <p>
            Donau-Universität-Krems / Gesellschaft für Know How, Transfers in Architektur
            und Bauwesen m.b.H. / BPHL Architekten v. Bassewitz, Patschan, Lüpertz,
            Limbrock GmbH, Architekturbüro Rossmann und Partner / Universität Stuttgart /
            TU-Braunschweig / Fachhochschule Hamburg / Fachhochschule Hildesheim /
            Arkitekter KHRAS, Architektengemeinschaft Maier, Weinbrenner, Single /
            Architektencontor Magdeburg / Fachhochschule Aachen / Fachhochschule Biberach
            / Fachhochschule Coburg, BDA Kreisverband Würzburg - Unterfranken / BDA
            Stuttgart / Oberste Baubehörde im bayrischen Staatsministerium des Inneren /
            Gewers Kühn & Kühn Architekten
          </p>
        </div>
      </div>
    </section>

    <section class="container mx-auto max-w-4xl py-16">
      <h3>Schreiben Sie uns</h3>
      <div>
        <div class="flex flex-wrap -m-2">
          <div class="p-2 w-1/2">
            <div class="relative">
              <label for="name" class="leading-7 text-sm text-gray-600">Name</label>
              <input
                type="text"
                id="name"
                name="name"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
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
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
          </div>
          <div class="p-2 w-full">
            <div class="relative">
              <label for="message" class="leading-7 text-sm text-gray-600">Nachricht</label>
              <textarea
                id="message"
                name="message"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"
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

  </main>
</template>
