<template>
    <section class="plates">
        <v-row>
            <v-col offset-xl="1" lg='12' xl="10" class="d-flex justify-space-around">
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/arrow.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Szansa na rozwój własnego biznesu
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/hands-helping.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Brak wymaganego kapitału i zero opłat na start
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/star.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Współpraca z liderem rynku
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/business-center.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Prosty model biznesowy
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/coins.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Atrakcyjne wynagrodzenie
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/hand-holding-heart.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Profesjonalna pomoc na każdym etapie
                    </div>
                </div>
                <div class="card">
                    <div class="card-icon">
                        <img src="../../assets/icons/two-persons.svg" alt="reasons">
                    </div>
                    <div class="card-text">
                        Ponad 30 tys. zadowolonych uczniów
                    </div>
                </div>
            </v-col>
        </v-row>
    </section>
</template>

<style scoped>
.plates {
    padding-bottom: 118px;
}

.card {
    display: inline-block;
    width: 179px;
    height: 201px;
    background: #F5EFF6 0% 0% no-repeat padding-box;
    border-radius: 15px;
}

.card-icon {
    padding: 26px 47.85px 14px 47.85px;
}

.card-icon img {
    width: 75px;
    height: 67px;
}

.card-text {
    padding: 0 8px;
    font-weight: 400;
    font-size: 16px;
    text-align: center;
    color: #813188;
}
</style>