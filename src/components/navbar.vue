<template>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <v-img alt="Vuetify Logo" class="shrink mr-2" contain src = "@/assets\logo.png" transition="scale-transition" width="40"/>

        <label>{{$const.APP_NAME}}</label>
      </div>

      <v-spacer></v-spacer>

      <v-btn text>login</v-btn>
      <v-icon>mdi-account-circle</v-icon>
    </v-app-bar>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>