<template>
    <nav class="navbar navbar-expand-lg bg-primary">
        <div class="container justify-content-eventy">
            <router-link to="/" class="navbar-brand">
                <span class="material-icons">home</span>
            </router-link>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">


                <router-link to="/" class="nav-link active" aria-current="page">
                    <span class="material-icons-round">home</span>
                </router-link>


                <router-link to="/about" class="nav-link active" aria-current="page">
                    <span class="material-icons-round">info</span>
                </router-link>


                <router-link to="/posts" class="nav-link active" aria-current="page">
                    <span class="material-icons-round">featured_play_list</span>
                </router-link>

                <!-- ... otros elementos ... -->

            </div>
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
    background-color: grey;
    padding: 0.3em;
    border-radius: 50%;
}
</style>