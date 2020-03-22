<template>
    <main class="pt-12 lg:pt-26 px-6 max-w-3xl mx-auto">
        <h1 class="text-3xl font-bold">La Page <span class="text-4xl" >111</span></h1>
        <p class="py-10 text-sm italic text-left">
            La page 111 à la sauce Osloite:
            <br class=""> le 11e mot tiré de la page 111, piochés dans 11 livres, mixés et livrés à l'imagination de Madame La duchesse de Camache: 
        </p>
        <p class="py-10 text-left">
            Nous étions tous des <span class="">fils</span> de notre <span class="">temps</span>.
            <br>Dans des <span class="">Banlieues-Dodo</span> <span class="">étalés</span> dans des coins de périphéries oubliés.
            <br>Au-delà de la <span class="">réflexion</span> de Dieu et du Patron.
            <br>Réalités à <span class="">portes</span> fermées. <span class="">Lèvres</span> silenciées. Il n'y a pas assez de livres à <span class="">lire</span>. <span class="">Beaucoup</span> d'amertume dans 10m<sup>2</sup>.
            <br>On se <span class="">trouve</span> perdues dans une pièce de théâtre que l'on <span class="">joue</span> malgré nous-même.
        </p>

        <h2 class="pt-10 text-left">Livres desquels furent tirés les mots:</h2>
        <p class="py-4 text-left text-gray-700 italic text-sm">
          fils: 'Tsubaki',
          <br>temps: 'Hamaguri',
          <br>banlieuesDodo: "Petit Cours d'auto-défense intellectuelle",
          <br>etales: 'Hotaru',
          <br>reflexion: 'La Chambre Claire',
          <br>portes: 'Peer Gynt',
          <br>levres: "Dans le jardin de l'ogre",
          <br>lire: 'Sérotonine',
          <br>beaucoup: 'Wasurenagusa',
          <br>trouve: 'La château de ma mère',
          <br>joue: 'Tsubame'
        </p>
    </main>
</template>

<script>
export default {
  name: 'Main',
  props: {
    title: String,
    story: String
  },
  data: function() {
    return {
      fils: 'Tsubaki',
      temps: 'Hamaguri',
      banlieuesDodo: "Petit Cours d'auto-défense intellectuelle",
      etales: 'Hotaru',
      reflexion: 'La Chambre Claire',
      portes: 'Peer Gynt',
      levres: "Dans le jardin de l'ogre",
      lire: 'Sérotonine',
      beaucoup: 'Wasurenagusa',
      trouve: 'La château de ma mère',
      joue: 'Tsubame'
    }
  },
  methods: {
    displayBook: function(word) {
        const spanHovered = document.getElementById(word);
        const insertReference = () =>  spanHovered.innerText = this[word];
        const displayReference = () => {
          insertReference();
          spanHovered.classList.remove('hidden');
          spanHovered.classList.add('flex');
        }
      return displayReference()
    },
    hideBook: () => {
      return console.log('wazai')
    }
  }
}
</script>

<style>

</style>