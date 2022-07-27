<template>
  <v-app>
    <v-img max-height="100vh" alt="background image" src="@/assets/bgPoster.png">
    <v-main>
      <router-view/>
    </v-main>
    </v-img>
    <v-app-bar
      app
      class="index"
      dark
      height="50px"
    >
    <a href="https://github.com/brissonkyle" class="white--text"><h4 class="ml-16"><strong>KYLE</strong> BRISSON</h4></a>
      <v-spacer></v-spacer>
      <a class="ma-4 white--text" href="https://github.com/brissonkyle">GitHub</a>
    </v-app-bar>
    <AboutPage/>
    <ProjectPage/>
    <ContactPage/>
  </v-app>
</template>

<script>
import AboutPage from './components/AboutPage.vue';
import ProjectPage from './components/ProjectPage.vue';
import ContactPage from './components/ContactPage.vue';

export default {
  components: { 
    AboutPage,
    ProjectPage,
    ContactPage 
  },
  name: 'App',

  data: () => ({
    
  }),

  methods: {
    
  },
};
</script>


<style scoped>
a {
  text-decoration: none;
}
</style>