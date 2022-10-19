<template>
  <main>
    <HeroStartpage />
    <section class="container mx-auto max-w-4xl py-16">
      <h2 class="title">Architektur Exkursionen</h2>
      <h3 class="subtitle">in Vorarlberg und International</h3>
      <p>
        architektur INFORM ist seit 1998 auf die Organisation und Durchführung von Exkursionen, Führungen, Touren und Reisen zu zeitgenössischer Architektur in Vorarlberg, Österreich und seit dem Jahre 2003 auch weltweit spezialisiert.
      </p>
    </section>
    <section class="container px-5 pb-24 mx-auto">
      <h3>Geplante Touren</h3>
      <TripList />
    </section>

    <!--
      <section class="container mx-auto max-w-4xl py-16">
        <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Aktuelle Reisen</h3>
        <posts post-type="blog" :amount="1" />
      </section>
    -->


    <section class="container mx-auto max-w-4xl py-16 pt-8 border-t border-gray-300">
      <div class="flex gap-8 mb-16">
        <div class="w-1/2">
          <h3 class="text-xl text-gray-900 font-semibold mb-2">Exklusive Zutritte</h3>
          <p>Meine langjährige Erfahrung in diesem Bereich und die persönlichen Kontakte ermöglichen ihnen auf diesen Touren/Exkursionen/Reisen auch Einblicke und exklusive Zutritte zu Orten und Gebäuden, die ihnen sonst verschlossen bleiben.</p>
        </div>
        <div class="w-1/2">
          <h3 class="text-xl text-gray-900 font-semibold mb-2">Organisation</h3>
          <p>Wir unterstützen Sie auch gerne bei der Organisation ihrer Vereins- und/oder Büroreise. Die Herausforderung für die Organisatoren liegt dabei darin, immer wieder etwas ganz Besonderes zu bieten. Bei architektur INFORM buchen Sie mich als Planerin, Organisatorin und Leiterin Ihrer Architektur-Exkursion. Die Destination, der Termin und die Gruppengrösse sind nach Wunsch frei wählbar.</p>
        </div>
      </div>
      <div class="flex gap-8">
        <div class="w-1/2">
          <h3 class="text-xl text-gray-900 font-semibold mb-2">Experten vor Ort</h3>
          <p>In den einzelnen Destination erläutern Ihnen Fachleute, Architekten, Bauherren als Referenten spannend und authentisch das Baugeschehen und die Technik, aber auch historische und gesellschaftliche Aspekte.</p>
        </div>
        <div class="w-1/2">
          <h3 class="text-xl text-gray-900 font-semibold mb-2">Persönlich</h3>
          <p>architektur INFORM eröffnet Wege zu einer zeitgemässen Weiterbildung und ist durch Begegnungen und eigenes Erleben eine persönliche und berufliche Bereicherung. Genau dies ist unsere Motivation und treibende Kraft für ein einzigartiges Reiseprodukt, das mehr bietet als bloss unterwegs zu sein.</p>
        </div>
      </div>
    </section>

  </main>
</template>