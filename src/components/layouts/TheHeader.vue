<template>
    <nav>
        <v-app-bar
        flat
        app
        >
        <v-row style="height: 64px" class="d-flex justify-space-around">
            <v-col  lg="2">
                <img width="200" src="../../assets/logo/main_logo.webp" alt="Tutore">
            </v-col>
            <v-col style="height: 64px" lg="3" class="d-flex justify-space-around align-center">
                <div>
                    <v-icon color="#813188">facebook</v-icon>
                    <v-icon color="#813188">facebook</v-icon>
                    <v-icon color="#813188">facebook</v-icon>
                </div>
                <v-btn elevation="2" dark outlined color="#813188">Strona firmowa</v-btn>
            </v-col>
            <v-col class="pa-1" lg="1">
                <v-select style="width: 100px" label="Polski" outlined></v-select>
            </v-col>
        </v-row>
        </v-app-bar>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>