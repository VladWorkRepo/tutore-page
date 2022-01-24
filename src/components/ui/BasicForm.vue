<template>
    <form :class="mode">
        <v-row class="d-flex align-end justify-center">
            <v-col xl='3' lg="4">
                <label class="inputLabel" :class="textColor" for="name">Imię</label>
                <input class="inputField" type="text" id="name" />
            </v-col>
            <v-col xl='3' lg="4">
                <label class="inputLabel" :class="textColor" for="name">Nazwisko</label>
                <input  class="inputField" type="text" id="name" />
            </v-col>
            <v-col xl='3' lg="4">
                <label class="inputLabel" :class="textColor" for="name">Numer telefonu</label>
                <input class="inputField" type="text" id="name" />
            </v-col>
            <v-col xl='3' lg="4">
                <button>Wyślij</button>
            </v-col>
        </v-row>
        <v-row>
            <v-col xl='12' lg="12">
                <input class="checkboxInput" id="check" type="checkbox" >
                <label class="checkboxLabel" :class="textColor" for="check">
                    Potwierdzam zapoznanie się z klauzulą informacyjną dotyczącą przetwarzania moich danych osobowych przez Music & More Sp. z o.o. oraz wyrażam zgodę na kontakt telefoniczny w celach biznesowych.
                </label>
            </v-col>
        </v-row>
    </form>
</template>

<script>
export default {
    props: ['mode','textColor']
}
</script>

<style scoped>
form {
    min-height: 342px;
    padding: 84px 220px 84px 208px;
}

.inputField {
    width: 328px;
    height: 60px;
    background: #FCFCFC 0% 0% no-repeat padding-box;
    box-shadow: inset 0px 3px 6px #00000017;
    border: 1px solid #707070;
    border-radius: 15px;
    opacity: 0.6;
}

.inputLabel {
    width: 197px;
    height: 35px;
    margin-left: 11px;
    display: block;
    color: #372E3B;
    font-size: 25px;
    font-style: normal;
    font-weight: 500;
    line-height: 36px;
}

button {
    width: 307px;
    height: 63px;
    background: #E72F84 0% 0% no-repeat padding-box;
    border: 1px solid #E72F84;
    border-radius: 15px;
    color: #FCFCFC;
    font-size: 31px;
    font-weight: bold;
}

button:hover {
    background: #E72F8499 0% 0% no-repeat padding-box;
    border: 1px solid #E72F84;
    opacity: 0.6;
}

.checkboxLabel {
    display: block;
    margin-top: -22px;
    margin-left: 20px;
    font-size: 12px;
    color: #372E3B;
    font-weight: 400;
}

.colored-bg {
    background-color: #36348A;
}

.white-text {
    color: #FCFCFC;
}

@media screen and (max-width: 1450px) {
form {
   padding: 84px 100px 84px 100px;
  }
}

@media screen and (max-width: 450px) {
form {
   padding: 84px 25px 84px 25px;
}

.inputField {
    width: 100%;
    height: 60px;
    background: #FCFCFC 0% 0% no-repeat padding-box;
    box-shadow: inset 0px 3px 6px #00000017;
    border: 1px solid #707070;
    border-radius: 15px;
    opacity: 0.6;
}

.inputLabel {
    width: 220px;
    height: 35px;
    margin-left: 11px;
    display: block;
    color: #372E3B;
    font-size: 25px;
    font-style: normal;
    font-weight: 500;
    line-height: 36px;
}

button {
    width: 100%;
    height: 63px;
    background: #E72F84 0% 0% no-repeat padding-box;
    border: 1px solid #E72F84;
    border-radius: 15px;
    color: #FCFCFC;
    font-size: 31px;
    font-weight: bold;
}
.white-text {
    color: #FCFCFC;
}
}
</style>