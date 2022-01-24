<template>
    <section class="step">
        <v-row class="d-flex align-end">
            <v-col offset-xl='1' offset-lg='0' offset-md='0' offset-sm='1' cols='12' xl='4' lg='6' md='6' sm='10' class="step-bg d-flex justify-center">
                <img src="../../assets/bg/steps-bg.png" alt="#">
            </v-col>
            <v-col offset-xl='1'  offset-lg='0' offset-md='0' offset-sm='1' cols='12' xl='4' lg='5' md='6' sm='10'>
                <h2 class="steps-title">Start krok po kroku</h2>
                <div class="steps">
                    <div class="steps-content">
                        <h3>Etap 1- Szkolenie w siedzibie firmy</h3>
                        <div class="steps-text">
                            W pierwszym etapie wprowadzimy Cię do świata edukacji online podczas kilkudniowego szkolenia - z naszej oferty i technik sprzedaży. 
                        </div>
                    </div>
                    <div class="steps-content">
                        <h3>Etap 2 - Szkolenie w terenie</h3>
                        <div class="steps-text">
                            Kolejnym krokiem jest minimum dwudniowe szkolenie w terenie. Nauczymy Cię jak zaprezentować ofertę firmy oraz jak przeprowadzać efektywne rozmowy z rodzicami, żeby owocowały one zapisem na zajęcia. 
                        </div> 
                    </div>
                    <div class="steps-content">
                        <h3>Etap 3 - Współpraca</h3>
                        <div class="steps-text">
                            Witamy w sieci partnerskiej Tutore! Od teraz możesz liczyć na pełne wsparcie w każdym aspekcie naszej współpracy.
                        </div>
                    </div>          
                </div>
            </v-col>
        </v-row>
    </section>
</template>

<style scoped>
.step {
    padding-bottom: 153px; 
}
.step-bg img {
    width: 100%;
}
.steps {
    margin-top: 38px;
}
.steps-content {
    margin-top: 28px;
}

.steps-title {
    font-size: 42px;
    font-weight: 600;
    line-height: 42px;
    color: #372E3B;
}

.steps-content h3 {
    font-size: 23px;
    font-weight: 600;
    color: #813188;
}

.steps-text {
    font-size: 20px;
    font-weight: 400;
    color: #372E3B;
}
</style>