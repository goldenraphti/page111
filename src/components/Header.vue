<template>
    <header class="p-2 shadow md:shadow-xl">
        <div class="flex mx-auto justify-between items-center max-w-5xl ">
            <div>
                <img alt="Hello Kitty" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQOR5DROAF1rLqG86vnsXOGVCk8anYQwcjzbEkT5ndDrZu-Tg2RTw&s" class="w-12 h-12" >
            </div>
            <div>
                <img alt="Voldemort" src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fstatici.behindthevoiceactors.com%2Fbehindthevoiceactors%2F_img%2Fchars%2Flord-voldemort-harry-potter-and-the-deathly-hallows-part-2-the-video-game-32.1.jpg&f=1&nofb=1" class="w-12 h-12" >
            </div>
            <!-- <div>
                <nav><ul class="flex">
                    <li class="px-6">1</li>    
                    <li class="px-6">2</li>    
                </ul></nav>
            </div> -->
        </div>
    </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
    background: rgb(229,132,125);
    background: linear-gradient(90deg, rgba(229,132,125,1) 0%, rgba(229,132,125,1) 25%, rgba(0,0,0,1) 75%, rgba(0,0,0,1) 100%);
}
</style>
