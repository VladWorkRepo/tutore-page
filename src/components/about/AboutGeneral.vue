<template>
   <basic-about-template :title="title" :content="content" :paragraph="paragraph">
       <img src="../../assets/bg/about-general-bg.png" alt="">
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
            title: 'Kim jesteśmy i czym się zajmujemy?',
            content: "Tutore to jeden z liderów branży edukacyjnej w Polsce. Prowadzimy najlepsze na rynku kursy online dla dzieci, młodzieży i dorosłych. Nasze wieloletnie doświadczenie, zdobyte w pracy z tysiącami dzieci w całej Polsce, pozwala nam trafnie oceniać potrzeby uczestników naszych kursów oraz spełnić ich oczekiwania.",
            paragraph: 'Szeroki zakres tematyczny naszych kursów pozwala każdemu znaleźć coś dla siebie, a wykwalifikowana kadra i wysoka jakość zajęć sprawia, że uczestnicy zostają z nami na lata.'
            
        };
    }    
}

</script>
