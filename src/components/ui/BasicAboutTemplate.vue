<template>
    <section class="about">
        <v-row>
            <v-col offset-xl='1' offset-lg='0' offset-md='2' lg='6' xl='6' md='8' class="d-flex justify-center align-center">
                <div class="about-text">
                    <h2 class="about-text_title">{{ title }}</h2>
                    <div class="about-text_content">
                        {{ content }}
                        <br><br>
                        {{ paragraph }}
                    </div>
                </div>   
            </v-col>
            <v-col offset-xl='0' offset-md='2' offset-lg='0' xl='5' lg='6' md='8' class="about-wrap">
                 <div class="about-bg">
                    <slot></slot>
                </div>
            </v-col>
        </v-row>
    </section>
</template>

<script>
export default {
    props: ['title', 'content', 'paragraph']
}
</script>

<style scoped>
.about {
    display: flex;
    padding-bottom: 140px;
}

.about-text_title {
    font-size: 42px;
    line-height: 38px;
    color: #372E3B;
}

.about-text_content {
    width: 630px;
    margin-top: 45px;
    font-weight: 400;
    font-size: 20px;
    color: #372E3B;
}

.about-wrap {
    display: flex;
    justify-content: start;
}

.about-bg img{
        width: 100%;
    }

@media screen and (max-width: 1904px) {
    .about-text_title {
        padding: 0 40px 0 40px;
    }
    .about-text_content {
        width: 600px;
        padding: 0 40px 0 40px;
    }
}

@media screen and (max-width: 1263px) {
    .about-text_content {
        width: 800px;
    }
    .about-wrap {
        display: flex;
        justify-content: center;
    }
}
</style>