<template>
  <v-app>
    <navbar></navbar>
    
    <v-main>
      <router-view/>
      <!-- <home/> -->
      <trial/>
      
    </v-main>
  </v-app>
  
  
</template>

<script>
import navbar from './components/navbar.vue';
import home from './components/home.vue';
import trial from './components/trial.vue';



export default {
  name: 'App',

  data: () => ({
    //
  }),
  components :{ navbar , home, trial}
};
</script>
<style>
 @import url('@/assets/styles.css');
</style>
