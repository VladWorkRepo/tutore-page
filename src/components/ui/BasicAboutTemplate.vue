<template>
    <section class="about">
        <v-row>
            <v-col offset-lg='1' lg='6' class="d-flex justify-center align-center">
                <div class="about-text">
                    <h2 class="about-text_title">{{ title }}</h2>
                    <div class="about-text_content">
                        {{ content }}
                        <br><br>
                        {{ paragraph }}
                    </div>
                </div>   
            </v-col>
            <v-col lg='5' class="d-flex justify-start">
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
</style>