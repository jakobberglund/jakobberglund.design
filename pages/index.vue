<template>
  <div class="wrapper">
    <div class="inner">
      <h1>
        I’m Jakob Berglund, a freelancing front-end lead and web developer
        specializing in design systems.
      </h1>
      <p>
        <a href="mailto:contact@jakobberglund.com">Contact me</a> for inquiries
        about work, workshops or general geekery.
      </p>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped>
.wrapper {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 2rem;
}

h1 {
  max-width: 35ch;
  font-size: clamp(1rem, calc(1rem + 2vw), 2rem);
  margin-bottom: 1em;
}
</style>
