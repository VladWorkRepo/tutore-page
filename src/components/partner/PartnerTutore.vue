<template>
    <section class="partner">
        <v-row class="d-flex align-center">
            <v-col xl='5' lg='6' class='partner-bg'>
                <img src="../../assets/bg/partner-tutore-bg.png" alt="#">
            </v-col>
            <v-col offset-xl='1' xl='5' lg='6'>
                <h2 class="partner-title">Czym zajmuje się Partner Tutore?</h2>
                <p>Twoim zadaniem będzie reprezentowanie szkoły Tutore na lokalnym rynku. Do Twoich obowiązków będzie należało:</p>
                <ul class="respons">
                    <li class="respons-item">
                        <div class="respons-item_icon">
                             <i class="fas fa-check" style="font-size:24px; color:#813188"></i>
                        </div>
                        <div class="respons-item_text">
                            Przedstawianie oferty kursów dla dzieci i dorosłych
                        </div>
                    </li>
                    <li class="respons-item">
                        <div class="respons-item_icon">
                            <i class="fas fa-check" style="font-size:24px; color:#813188"></i>
                        </div>
                        <div class="respons-item_text">
                            Zapraszanie na zajęcia pokazowe dzieci i ich rodziców
                        </div>
                    </li>
                    <li class="respons-item">
                        <div class="respons-item_icon">
                             <i class="fas fa-check" style="font-size:24px; color:#813188"></i>
                        </div>
                        <div class="respons-item_text">
                            Zapisywanie dzieci i rodziców na kursy stałe
                        </div>
                    </li>
                    <li class="respons-item">
                        <div class="respons-item_icon">
                              <i class="fas fa-check" style="font-size:24px; color:#813188"></i>
                        </div>
                        <div class="respons-item_text">
                            Stały kontakt z klientami
                        </div>
                    </li>
                    <li class="respons-item">
                        <div class="respons-item_icon">
                              <i class="fas fa-check" style="font-size:24px; color:#813188"></i>
                        </div>
                        <div class="respons-item_text">
                            Umacnianie pozycji firmy na rynku lokalnym
                        </div>
                    </li>
                    <li class="respons-item">
                        <div class="respons-item_icon">
                              <i class="fas fa-check" style="font-size:24px; color:#813188"></i>
                        </div>
                        <div class="respons-item_text">
                            Budowanie pozytywnego wizerunku firmy
                        </div>
                    </li>
                    <li class="respons-item">
                        <div class="respons-item_icon">
                              <i class="fas fa-check" style="font-size:24px; color:#813188"></i>
                        </div>
                        <div class="respons-item_text">
                            Działania wzmacniające rozpoznawalność marki Tutore.
                        </div>
                    </li>
                </ul>
            </v-col>
        </v-row>
    </section>
</template>

<style scoped>
.partner-bg img{
    width: 100%;
}
.partner-title {
    font-size: 42px;
    line-height: 42px;
    font-weight: 600;
    color: #372E3B;
}

p {
    margin: 57px 0;
    font-size: 27px;
    font-weight: 400;
    color: #372E3B;
}

ul {
    list-style-type: none;
}

.respons-item {
    display: flex;
    align-items: center;
}

.respons-item .respons-item_text {
    margin-left: 20px;
    font-size: 22px;
    font-weight: 400;
    line-height: 40px;
}
</style>