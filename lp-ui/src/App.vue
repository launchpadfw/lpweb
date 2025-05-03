<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBarView from './components/NavBar.vue'
</script>

<template>
  <NavBarView />

  <RouterView />
</template>