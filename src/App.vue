<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
        <span class="font-weight-light">MATERIAL DESIGN </span>
      </v-toolbar-title> 
      <v-spacer></v-spacer>
      <router-link to="/">
      <v-btn flat>
        <span class="mr-2">Home </span>
      </v-btn>
      </router-link>

      <router-link to="/post">
      <v-btn flat>
        <span class="mr-2">Post</span>
      </v-btn>
      </router-link>

    <router-link to="/user">
      <v-btn flat>
        <span class= "mr-2">User</span>
      </v-btn>
      </router-link>
    
    
    </v-toolbar>

    <v-content>
     <router-view/>
     
    </v-content>
  </v-app>
</template>
<script>
export default {
  name: 'App',
  components: {
    
  },
  data () {
    return {
      //
    }
  }
}
</script>
