<template>
  <v-app>
    <the-header></the-header>
  </v-app>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';

export default {
  components: {
    TheHeader
  },
};
</script>

<style>
* {
  font-family: 'Poppins', sans-serif;
}
</style>
