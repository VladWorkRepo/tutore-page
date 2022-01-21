<template>
  <v-app>
    <the-header></the-header>
    <v-main class="pa-0">
      <the-promo></the-promo>
      <basic-form></basic-form>
      <upper-plates></upper-plates>
      <about-general></about-general>
      <about-business></about-business>
      <step-by-step></step-by-step>
      <partner-tutore></partner-tutore>
      <down-plates></down-plates>
      <be-partner></be-partner>
      <basic-form mode="colored-bg" textColor="white-text"></basic-form>
    </v-main>
    
  </v-app>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import ThePromo from './components/layouts/ThePromo.vue';
import BasicForm from './components/ui/BasicForm.vue';
import UpperPlates from './components/plates/UpperPlates.vue';
import DownPlates from './components/plates/DownPlates.vue';
import AboutGeneral from './components/about/AboutGeneral.vue';
import AboutBusiness from './components/about/AboutBusiness.vue';
import StepByStep from './components/partner/StepByStep.vue';
import PartnerTutore from './components/partner/PartnerTutore.vue';
import BePartner from './components/partner/BePartner.vue';


export default {
  components: {
    TheHeader,
    ThePromo,
    BasicForm,
    UpperPlates,
    DownPlates,
    AboutGeneral,
    AboutBusiness,
    StepByStep,
    PartnerTutore,
    BePartner
  },
};
</script>

<style>
* {
  font-family: 'Poppins', sans-serif;
}
</style>
