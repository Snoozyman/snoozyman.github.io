<script setup>
import { RouterView } from 'vue-router'
import NavBar from '@/components/NavBar.vue'

const pageTitle = 'Snoozyman'
</script>

<template>
  <NavBar :title="pageTitle" />
  <header>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>MY</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@1.0.0/css/bulma.min.css" />
    <!--<img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->
  </header>
  <main>
    <RouterView />
  </main>
</template>
<style scoped>
.wrapper {
  margin-top: 1%;
  background-color: rgb(234, 160, 160);
}
</style>
