<template>
  <footer class="footer items-center p-4 bg-base-200 text-base-content mt-16">
    <div class="items-center grid-flow-col">
      <p>© {{ new Date().getFullYear() }} LaunchPad. All rights reserved.</p>
    </div>
    <div class="grid-flow-col gap-4 md:place-self-center md:justify-self-end">
      <a href="https://github.com/your-org/launchpad" target="_blank" class="link link-hover">GitHub</a>
      <router-link to="/sponsor" class="link link-hover">Sponsor</router-link>
    </div>
  </footer>
</template>

<script setup>
// No logic required for static footer
</script>
