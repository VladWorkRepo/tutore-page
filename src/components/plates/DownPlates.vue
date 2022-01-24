<template>
    <section class="plates">
        <v-row>
            <v-col xl='3' lg='5'>
                <h2 class="plates-title">Dlaczego warto?</h2>
            </v-col>
            <v-col cols='12' xl='12' lg='12' md='12' sm='12' class="d-flex justify-space-around flex-wrap">
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/hands-helping.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Nie oczekujemy od Ciebie wkładu własnego ani opłat za przystąpienie do programu.
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/home.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                       Na starcie nie musisz także inwestować w wynajem biura ani wymyślać skomplikowanego systemu CRM.
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/coins.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Oferujemy atrakcyjne wynagrodzenie zależne od Twojego zaangażowania
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/hand-holding-heart.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Zapewniamy wdrożenie i stałe wsparcie podczas współpracy.
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/arrow.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Współpracujesz z liderem na rynku edukacji - to szansa na rozwój swojego biznesu pod skrzydłami doświadczonego partnera.
                    </div>
                </div>
            </v-col>
        </v-row>
    </section>
</template>

<style scoped>
.plates {
    padding: 145px 100px 0 100px;
}

.plates .plates-title {
    font-size: 42px;
    color: #813188;
    font-weight: 600;
}

.card {
    display: inline-block;
    width: 325px;
    height: 410px;
    margin-top: 63px;
    background: #F5EFF6 0% 0% no-repeat padding-box;
    border-radius: 15px;
}

.card-icon {
    padding: 60px 90px 50px 90px;
}

.card-icon img {
    width: 141px;
    height: 125px;
}

.card-text {
    padding: 0 20px;
    font-weight: 400;
    font-size: 20px;
    color: #813188;
}

@media screen and (max-width: 1904px) {
    .plates {
        padding: 145px 50px 0 50px;
    }
}

@media screen and (max-width: 600px) {
    .card {
        width: 290px;
        height: 455px;
    }
}

</style>