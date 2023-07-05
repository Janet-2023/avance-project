<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/local">Local</RouterLink>
        <RouterLink to="zonasreparto">zonA DE REPARTO</RouterLink>

      </nav>

  </header>

  <RouterView />
</template>


<style>

nav{
  display: flex;
  justify-content: space-between;
}


</style>