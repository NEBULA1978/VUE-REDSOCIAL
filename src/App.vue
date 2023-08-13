<template>
  <!-- Componente -->
 <NavComp />
  <!-- Navegador  rutas -->
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/posts">Posts</router-link>
  </nav>
  <router-view />
</template>

<script scope>
import NavComp from '@/components/NavComp.vue'
export default{
  name:"App",
  components:{
    NavComp
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
