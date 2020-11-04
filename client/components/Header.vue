<template>
  <v-toolbar dark color="blue">
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title class="white--text">
      <nuxt-link to="/">Accueil</nuxt-link>
      <nuxt-link to="/showroom">ShowRoom</nuxt-link>
      <nuxt-link to="/connexion">Connexion</nuxt-link>
      <nuxt-link to="/admin">Admin</nuxt-link>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn to="/" icon>
      <v-icon>refresh</v-icon>
    </v-btn>
  </v-toolbar>
</template>

<script>
export default {
  data() {
    return {}
  },
}
</script>

<style scoped></style>
