<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBarView from './components/NavBar.vue'
import FooterView from './components/Footer.vue'
</script>

<template>
  <NavBarView />

  <RouterView />

  <FooterView />
</template>