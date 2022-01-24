<template>
    <nav>
        <v-app-bar
        flat
        style="height: 90px"
        >
        <v-app-bar-nav-icon class="hamburger" @click="drawer = !drawer"></v-app-bar-nav-icon>
        <v-container style="height: 96px">
            <v-row class="ma-0">
                <v-col offset-lg='1' offset-xl='2' lg='10' xl='8' style="height: 96px" class='d-flex align-center jusify-space-between'>
                    <img width="200" src="../../assets/logo/main_logo.webp" alt="Tutore">
                    <v-spacer></v-spacer>
                    <div class="action-btn">
                      <basic-head-buttons></basic-head-buttons>
                    </div>
                </v-col>
            </v-row>
        </v-container>
        </v-app-bar>

         <v-navigation-drawer class="nav-draw" app v-model="drawer" >
            <v-list>
                <v-list-item>
                    <v-list-item-content class="list-items">
                        <basic-head-buttons mode="column-direction" action-mode="social-mode">
                             <img width="200" src="../../assets/logo/main_logo.webp" alt="Tutore">
                        </basic-head-buttons>
                    </v-list-item-content>
                </v-list-item>
            </v-list>
        </v-navigation-drawer>
    </nav>
</template>

<script>
import BasicHeadButtons from '../ui/BasicHeadButtons.vue';

export default {
    components: {
        BasicHeadButtons
    },
    data() {
        return {
            drawer: false
        };
    }
}
</script>
<style scoped>
.nav-draw {
    display: none;
}
.hamburger {
    display: none;
    align-items: flex-end;
    color:#813188
}
.action-btn {
    margin-right: 0;
    display: flex;
    justify-content: flex-end;
}
.list-items {
    display: flex;
    flex-direction: row;
}
@media screen and (max-width: 3000px) {
.action-btn {
   width: 60%;
  }
}

@media screen and (max-width: 1904px) {
.action-btn {
   width: 70%;
  }
}

@media screen and (max-width: 900px) {
.hamburger {
   display: flex;
  }

.action-btn {
    display: none;
}

.nav-draw {
    display: block;
}
}
</style>