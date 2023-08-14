<template>
    <nav class="navbar navbar-expand-lg bg-primary">
        <div class="container justify-content-eventy">
          
           


                <router-link to="/" class="nav-link" aria-current="page">
                    <span class="material-icons-round">home</span>
                </router-link>


                <router-link to="/about" class="nav-link" aria-current="page">
                    <span class="material-icons-round">info</span>
                </router-link>


                <router-link to="/posts" class="nav-link" aria-current="page">
                    <span class="material-icons-round">featured_play_list</span>
                </router-link>

                <!-- ... otros elementos ... -->

            
        </div>
    </nav>
</template>

<script>
export default {
    name: "Navcom"
}
</script>

<style>
.material-icons-round {
    color: white;
    font-size: 1.4em;
    background-color: rgba(128, 128, 128, 0.162);
    padding: 0.3em;
    border-radius: 50%;
    margin: 0.1em;
}


</style>

<!-- Voy video2 minuto10:53 -->