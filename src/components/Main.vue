<template>
    <main class="pt-12 lg:pt-32 px-6 max-w-3xl mx-auto">
        <h1 class="text-3xl font-bold font-serif">La Page <span class="text-4xl" >111</span></h1>
        <p class="py-10 text-sm italic text-left">
            La page 111 à la sauce Osloite:
            <br class=""> le 11e mot tiré de la page 111, piochés dans 11 livres, mixés et livrés à l'imagination de Madame La duchesse de Camache: 
        </p>
        <p class="py-10 text-left">
            Et voici le cadavre exquis de Laura
        </p>
    </main>
</template>

<script>
export default {
  name: 'Main',
  props: {
    title: String,
    story: String
  }
}
</script>

<style>

</style>