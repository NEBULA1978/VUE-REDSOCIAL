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

<!-- una aplicación que utiliza Vue Router para gestionar las rutas y componentes. En este código, estás definiendo la estructura básica de un componente principal de la aplicación, llamado App. Aquí tienes un resumen de lo que hace cada parte del código: Template: El bloque <template> contiene la estructura de la página. Aquí es donde se define la disposición visual y los elementos que se mostrarán en la interfaz de usuario. En este caso, tienes: NavComp: Aquí se muestra un componente llamado NavComp utilizando la etiqueta <NavComp />. Esto puede ser un componente personalizado definido en otro archivo llamado NavComp.vue. Navegación con enlaces de ruta: Se utilizan las etiquetas <router-link> para crear enlaces de navegación interna. Estos enlaces están configurados para dirigir a las rutas /, /about y /posts dentro de la aplicación. <router-view>: Este es un marcador de posición donde Vue Router renderizará el componente correspondiente según la ruta actual. Script: El bloque <script> contiene la lógica y la funcionalidad del componente App. Aquí tienes: import NavComp from '@/components/NavComp.vue': Esto importa el componente NavComp desde el archivo NavComp.vue. El @ se utiliza para referenciar la ruta base de los módulos en tu proyecto. export default { ... }: Aquí se define la configuración del componente App. Le estás dando un nombre (name: "App") y declarando que contiene el componente NavComp. Estilos: El bloque <style> contiene reglas de estilo que se aplican al componente App. En resumen, este fragmento de código define la estructura básica de un componente principal en una aplicación Vue.js que utiliza Vue Router para la navegación y tiene un componente personalizado NavComp para mostrar algún tipo de navegación adicional. La navegación principal se realiza a través de enlaces de ruta que cargan componentes específicos en el espacio reservado <router-view>. -->
