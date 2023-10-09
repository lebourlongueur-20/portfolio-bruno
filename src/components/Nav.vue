<script setup>
import NavLink from './NavLink.vue';
import { RouterLink } from 'vue-router';
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <RouterLink class="navbar-brand" url="/" to="/">Accueil</RouterLink>
      <button class="navbar-toggler" type="button" data-mdb-toggle="collapse" data-mdb-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <i class="fas fa-bars"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <NavLink url="/" text="Projets" />
          <NavLink url="/" text="À propos" />
        </ul>
      </div>
    </div>
  </nav>
</template>
