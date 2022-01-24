<template>

    <div class="actions" :class="mode">
          <div class="actions_social" :class="actionMode">
            <a href="https://pl.linkedin.com/company/tutore-edu?trk=ppro_cprof"><i class="fab fa-linkedin-in" style="font-size:24px; color:#813188"></i></a>
            <a href="https://www.facebook.com/tutore.eu/"><i class="fab fa-facebook" style="font-size:24px; color:#813188"></i></a>
            <a href="https://www.youtube.com/channel/UCPlfC3SOLzgYEP3fjlOisAQ"><i class="fab fa-youtube" style="font-size:24px; color:#813188" ></i></a>
        </div>
        <button onclick="location.href='https://tutore.eu/'" type="button" class="actions_button">Strona firmowa</button>
        <v-menu offset-y>
            <template v-slot:activator="{ on }">
                <button class="dropdown_button" v-on="on">
                    Polski
                    <i class="ml-5 fas fa-caret-down" style="font-size:8px; color:#707070" ></i>
                </button>
            </template>
            <!-- <v-list>
                <v-list-item >
                    langs goes here
                </v-list-item>
            </v-list> -->
        </v-menu>
        <slot class="slot"></slot>
    </div>
</template>

<script>
export default {
    props: ['mode', 'actionMode']
}
</script>

<style scoped>
.actions {
    width: 70%;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.actions_social {
    width: 25%;
    display: flex;
    justify-content: space-around;
    align-items: space-between;
}

.social-mode {
    width: 50%;
}

img {
    margin-top: 20px;
    margin-bottom: 30px;
}

.column-direction {
    height: 220px;
    display: flex;
    flex-direction: column-reverse;
    align-items: flex-start;
    justify-content: space-between;
}

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