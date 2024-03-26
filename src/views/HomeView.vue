<script setup></script>

<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <h1 class="title">Section</h1>
      <h2 class="subtitle">
        A simple container to divide your page into sections, like the one you're currently reading.
      </h2>
    </div>
  </section>
  <div class="columns">
    <div class="column">
      <section class="section">
        <h1 class="title">Introduction</h1>
        <p>Hello</p>
      </section>
    </div>
    <!--
    <div class="column">
      <section class="section">
        <h1 class="title">Introduction</h1>
        <p>Hello</p>
      </section>
    </div>
    -->
  </div>
</template>
<style scoped>
.hero-body {
  background-image: url('../assets/background.jpg');
  background-size: cover;
}
.title,
.subtitle {
  color: chocolate;
}
</style>
