<template>
    <div class="promo">
        <v-row>
            <v-col xl='12'>
                <div style="height:275px" class="d-flex align-end justify-center">
                    <h1 class="promo-title">Zostań Partnerem Tutore</h1>
                </div>
            </v-col>
        </v-row>
      
        <div style="height:181px" class="d-flex align-center justify-center">
           <button @click="scrollToElement('about')">Zobacz więcej</button>
        </div>
        
    </div>
</template>

<style scoped>
.promo {
    background: transparent url('../../assets/bg/promo_bg.jpg') center/cover no-repeat;
}

.promo .promo-title {
    padding: 0 10px 0 10px;
    text-align: center;
    color: #fff;
    font-size:65px;
    line-height:65px;
}

button {
    height: 80px;
    width: 400px;
    background-color: #fff;
    border-radius: 12px;
    font-size: 30px;
    font-weight: 700;
    transition: all 0.1s;
    color: #372E3B;
}
button:hover {
    background-color: #e6e1e7;
}
</style>