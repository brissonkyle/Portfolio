<template>
    <div class="box">
        <v-row class="text-center">
            <v-col cols="6" sm="12" md="6" lg="6">
                <v-img min-width="50vw" height="600px" src="@/assets/Me.jpg"></v-img>
            </v-col>
            <v-col cols="6" sm="12" md="6" lg="6">
                <h1 class="white--text style1"><strong>About</strong></h1>
                <p class="white--text">____________________________</p>
                <p class="white--text style"><strong>I am Kyle Brisson. I am a problem solver willing to go the extra mile for a solution. I strive on learning and intelligence and wish to bring the best built systems possible. Be it Full-Stack Applications to simple static ones im convinced I can can find a solution for you.</strong></p>
                <p class="white--text">____________________________</p>
            </v-col>
        </v-row>
    </div>
</template>

<script>
    export default {
        name : 'AboutPage',

        data() {
            return {
                
            }
        },
    }
</script>

<style lang="scss" scoped>
.box {
    width: 100%;
    height: 100vh;
    background-color: black;
}
.style {
    margin-right: 10px;
    margin-top: 5%;
    font-size: 25px;
    font-style: italic;
}
.style1 {
    margin-top: 15%;
}
</style>