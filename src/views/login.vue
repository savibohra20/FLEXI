<template>
    <div class="center">
        <v-row>
            <v-col cols="10" offset="1" sm="6" offset-sm="3" md="4" offset-md="4">
                <v-avatar color="surface-variant" rounded="0" size="95">
                    <v-img src="@/assets/logo.png"></v-img>
                </v-avatar>
                <v-text-field class="base" label="username" v-model="username "></v-text-field>
                    <v-text-field class="base" label="password" type="password" v-model="password"></v-text-field>
                    <v-btn class="base-inverted" block @click="authentication()">
                        Button
                    </v-btn>
                <!-- <h1>login page</h1> -->
            </v-col>
        </v-row>
    </div>
</template>
<script>
  export default {
    data() {
        return {
            username :"",
            password :"",
        }
    },
    
    methods: {
        authentication() {
            alert("login successfully")
        }
    },

  }
</script>