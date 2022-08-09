<template>
    <div class="box">
        <v-row class="text-center justify-center">
            <v-col cols="12">
                <h1 class="white--text"><strong>My Projects</strong></h1>
            </v-col>
            <v-col cols="4" sm="12" md="12" lg="4">
                <v-card height="225px"  dark>
                    <v-card-title class="justify-center"><strong>Pizza Website</strong></v-card-title>
                    <v-card-text class="white--text">
                        Beautiful Pizza website built with pure Html and CSS. Using well structured code and advanced CSS I was able to put together a beautiful piece of work.
                    </v-card-text>
                    <v-btn href="https://github.com/brissonkyle/PizzaProject" target="_blank" dark>
                        Pizza Time?
                    </v-btn>
                </v-card>
            </v-col>
            <v-col cols="4" sm="12" md="12" lg="4">
                <v-card height="225px"  dark>
                    <v-card-title class="justify-center"><strong>Foodie Project</strong></v-card-title>
                    <v-card-text class="white--text">
                        Full stack website. Front end build with Javscript framework, Vue 2. Back-end build with Python framework, Flask. Attached to a DB (DATABASE) using MySQL to speak to MariaDB.
                    </v-card-text>
                    <v-btn href="https://github.com/brissonkyle/FoodieProject" target="_blank" dark>
                        Mhmm Food!!
                    </v-btn>
                </v-card>
            </v-col>
            <v-col cols="4" sm="12" md="12" lg="4">
                <v-card height="225px" dark>
                    <v-card-title class="justify-center"><strong>MVP Stats</strong></v-card-title>
                    <v-card-text class="white--text">
                        Full stack website. Front-end build with Javascript framework, Vue 2. Back-end build with Python framework, Flask. Attached to a DB (DATABASE) using MySQL to speak to MariaDB.
                    </v-card-text>
                    <v-btn href="https://github.com/brissonkyle/MVPstats" target="_blank" dark>
                        Stats Baby!!
                    </v-btn>
                </v-card>
            </v-col>
        </v-row>
        <v-row class="white--text text-center justify-center">
            <v-col cols="12">
                <v-card dark>
                    <v-card-title class="justify-center">
                        Some Development Skills
                    </v-card-title>
                    <v-row>
                        <v-col cols="6" sm="12" md="12" lg="6">
                            <p>1. HTML</p>
                            <p>2. CSS</p>
                            <p>3. Javascript</p>
                            <p>4. Vue</p>
                        </v-col>
                        <v-col cols="6" sm="12" md="12" lg="6">
                            <p>5. Vuetify</p>
                            <p>6. Python</p>
                            <p>7. Flask</p>
                            <p>8. MySQL</p>
                        </v-col>
                    </v-row>
                </v-card>
            </v-col>
        </v-row>
    </div>
</template>

<script>
    export default {
        name : 'ProjectPage',

        data() {
            return {
                items: [
                    {
                        src : ''
                    },
                    {
                        src : ''
                    },
                    {
                        src : ''
                    },
                    {
                        src : ''
                    },
                    {
                        src : ''
                    },
                    {
                        src : ''
                    },
                ]
            }
        },
    }
</script>

<style lang="scss" scoped>
.box {
    background-color: rgb(79, 79, 79);
}
</style>