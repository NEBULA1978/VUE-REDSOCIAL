<template>
     <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
          <router-link router-link to="/" class="navbar-brand" >LOGO</router-link><routes-link></routes-link>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <router-link to="/" class="nav-link active" aria-current="page">Home</router-link>
               
              </li>
              <li class="nav-item">
                <a class="nav-link" >About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" >Posts</a>
              </li>

            </ul>
          </div>
        </div>
      </nav>
</template>