<template>
  <v-app>
    <the-header></the-header>
    <v-main>
      <the-promo></the-promo>
      <basic-form></basic-form>
    </v-main>
    
  </v-app>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import ThePromo from './components/layouts/ThePromo.vue';
import BasicForm from './components/ui/BasicForm.vue';

export default {
  components: {
    TheHeader,
    ThePromo,
    BasicForm
  },
};
</script>

<style>
* {
  font-family: 'Poppins', sans-serif;
}
</style>
