<template>
  <div id="app">
    <img class="pokemon--image" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/International_Pok%C3%A9mon_logo.svg/2560px-International_Pok%C3%A9mon_logo.svg.png" alt="">
    <h1>PokeGuía</h1>
    <hello-world></hello-world>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
*{
  text-align: center;
  font-family: 'Press Start 2P', cursive;
}
p{
  margin: 0;
}
.pokemon--image{
  width: 400px;
  margin: 40px 0;
}
h1{
  margin: 40px 0;
}
</style>
