<template>
    <form>
        <v-row class="d-flex align-end justify-center">
            <v-col lg="3">
                <label class="inputLabel" for="name">Imię</label>
                <input class="inputField" type="text" id="name" />
            </v-col>
            <v-col lg="3">
                <label class="inputLabel" for="name">Nazwisko</label>
                <input  class="inputField" type="text" id="name" />
            </v-col>
            <v-col lg="3">
                <label class="inputLabel" for="name">Numer telefonu</label>
                <input class="inputField" type="text" id="name" />
            </v-col>
            <v-col lg="3">
                <button>Wyślij</button>
            </v-col>
        </v-row>
        <v-row>
            <v-col lg="12">
                <input class="checkboxInput" id="check" type="checkbox" >
                <label class="checkboxLabel" for="check">
                    Potwierdzam zapoznanie się z klauzulą informacyjną dotyczącą przetwarzania moich danych osobowych przez Music & More Sp. z o.o. oraz wyrażam zgodę na kontakt telefoniczny w celach biznesowych.
                </label>
            </v-col>
        </v-row>
    </form>
</template>

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

</style>