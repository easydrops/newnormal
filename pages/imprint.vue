<template>
  <main class="bg-top flex flex-col p-8 relative bg-no-repeat main-bg-color">
    <section class="w-full max-w-5xl mx-auto">
      <div class="text-content entry-content clearfix text-black">
        <h2>Imprint</h2>
        <h4>Angaben gemäß § 5 TMG:</h4>
        <p>Kunstverein Wagenhalle </br> Innerer Nordbahnhof 1 </br> 70191 Stuttgart</p>
        <h5>Vertreten durch:</h5>
        <p>Weiny Fitui</br>
          Marvin Unger </br> <a href="mailto:info@newnormal2022.de">info@newnormal2022.de</a></p>
        <p>
          Ein Projekt des Kunstverein Wagenhalle.
          Gefördert im Impulsprogramm “Kultur trotz Corona” des Ministeriums für Wissenschaft, Forschung und Kunst Baden-Württemberg. Weitere Förderer sind das Kulturamt Stuttgart, Pop-Büro Stuttgart, Ritter Sport und pbb Stiftung.
          Partner sind contain’t, Sommer Cable und Freies Radio für Stuttgart.
        </p>
          
           <h5>Gestaltung</h5>
<p>Y-Thanh Võ</br>
  Maximilian Messer
</p>
<h5>Webdesign</h5>
<p>
Jan Hoydem
</p>

           <h5>Haftung</h5><p>
Trotz sorgfältiger inhaltlicher Kontrolle übernehmen wir keine Haftung für die Inhalte externer Links. Für den Inhalt der verlinkten Seiten sind ausschließlich deren Betreiber verantwortlich.
     
     </p> </div>
    </section>
  </main>
</template>

<script>
export default {
  async asyncData({ $content, error }) {
    let posts
    try {
      posts = await $content('projects').fetch()
    } catch (e) {
      error({ message: 'Projects not found' })
    }
    return { posts }
  },
}
</script>
