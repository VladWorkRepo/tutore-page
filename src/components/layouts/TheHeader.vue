<template>
    <nav>
        <v-app-bar
        flat
        app
        style="height: 90px"
        >
        <v-container style="height: 96px">
            <v-row class="ma-0">
                <v-col offset-lg='2' lg='8' style="height: 96px" class='d-flex align-center'>
                    <img width="200" src="../../assets/logo/main_logo.webp" alt="Tutore">
                    <v-spacer></v-spacer>
                    <div style="width: 40%" class="actions d-flex align-center justify-space-between">
                        <div style="width: 25%" class="actions_social d-flex justify-space-between">
                            <i class="fab fa-linkedin-in" style="font-size:24px; color:#813188"></i>
                            <i class="fab fa-facebook" style="font-size:24px; color:#813188"></i>
                            <i class="fab fa-youtube" style="font-size:24px; color:#813188" ></i>
                        </div>
                        <button class="actions_button">Strona firmowa</button>
                        <v-menu offset-y>
                            <template v-slot:activator="{ on }">
                                <button class="dropdown_button" v-on="on">
                                    Polski
                                    <i class="fas fa-caret-down" style="font-size:8px; color:#707070" ></i>
                                </button>
                            </template>
                            <v-list>
                                <v-list-item >
                                    <v-list-item-title>Francuski</v-list-item-title>
                                </v-list-item>
                            </v-list>
                        </v-menu>
                    </div>
                </v-col>
            </v-row>
        </v-container>
        </v-app-bar>

    </nav>
</template>

<style scoped>
.actions_button {
    width: 165px;
    height: 35px;
    font-weight: 500;
    color: #813188;
    border: 1px solid #813188;
    border-radius: 5px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
}

.actions_button:hover {
    background-color: #e6e1e7;;
}

.dropdown_button {
    width: 130px;
    height: 33px;
    border: 1px solid #afafaf;
    color: #707070;
    border-radius: 2px;
}

</style>