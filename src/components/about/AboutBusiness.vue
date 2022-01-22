<template>
    <basic-about-template :title="title" :content="content">
        <img src="../../assets/bg/about-business-bg.png" alt="#">
    </basic-about-template>
</template>

 <script>
 import BasicAboutTemplate from '../ui/BasicAboutTemplate.vue';
 export default {
     components: {
         BasicAboutTemplate
     },
     data() {
         return {
             title: "Kim jest Partner biznesowy Tutore?",
             content: "Partner Tutore to samodzielny przedsiębiorca, który jest zaangażowany i chce rozwijać własny biznes. W sieci partnerskiej stawiamy na prosty i sprawdzony model, zaczniesz osiągać wyniki już w pierwszym miesiącu współpracy. Zatem jeśli jesteś zmotywowany do osiągania wyników i chcesz rozwinąć swój biznes z liderem rynku zarabiając naprawdę duże pieniądze, dołącz do sieci partnerskiej Tutore. Naszym jedynym wymogiem jest otwarta działalność gospodarcza bądź gotowość do jej założenia."
         };
     }
 }
 </script>