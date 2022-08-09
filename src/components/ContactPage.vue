<template>
    <div class="box">
        <v-img width="100vw" src="@/assets/bg1.jpg">
        <v-row class="text-center justify-center style">
        <v-form>
            <v-card dark width="80%">
                <v-col cols="12">
                <h1 class="style1 white--text">Contact Me</h1>
            </v-col>
            <v-col class="color" cols="12">
                    <v-card-title class="justify-center">Reach Out</v-card-title>
                    <v-text-field color="success" v-model="name" label="Your Name" outlined class="pa-1"></v-text-field>
                    <v-text-field color="success" v-model="email" label="Your Email" outlined class="pa-1"></v-text-field>
                    <v-textarea color="success" v-model="message" label="Your Message" outlined class="pa-1"></v-textarea>
                    <v-btn type="submit" @click="sendEmail" dark class="mb-4 white--text">Submit</v-btn>
                    </v-col>
                    <h1><strong>My Socials</strong></h1>
                    <v-row class="justify-center">
                    <v-col cols="3">
                        <v-btn class="ma-3" dark><a class="white--text" href="https://facebook.com" target="_blank">Facebook</a></v-btn>
                    </v-col>
                    <v-col cols="3">
                        <v-btn class="ma-3" dark><a class="white--text" href="https://outlook.com" target="_blank">Outlook</a></v-btn>
                    </v-col>
                    <v-col cols="3">
                        <v-btn class="ma-3" dark><a class="white--text" href="https://www.linkedin.com/in/kyle-brisson-916aa4239/" target="_blank">LinkdIn</a></v-btn>
                    </v-col>
                    </v-row>
            </v-card>
        </v-form>
        </v-row>
        </v-img>
    </div>
</template>

<script>
import emailjs from '@emailjs/browser';

export default {
    name : 'ContactPage',
    data() {
    return {
        name: '',
        email: '',
        message: ''
        }
    },
    methods: {
        sendEmail() {
        emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', 'YOUR_USER_ID', {
            name: this.name,
            email: this.email,
            message: this.message
        })
    }
    }
}
</script>
