<template>
  <div>
    <v-app-bar
      color="#3700B3" dark
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Hello BD</v-toolbar-title>

      <v-spacer></v-spacer>

      <div>
        <router-link to="/about">
          <v-btn text>About</v-btn>
        </router-link>
        <router-link to="/contact">
          <v-btn text>Contact</v-btn>
        </router-link>
        <router-link to="/login">
          <v-btn text>Log in</v-btn>
        </router-link>
      </div>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
 a {
   text-decoration: none;
 }
</style>