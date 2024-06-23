<template>
  <v-app>
    <v-main>
      <v-container>
        <v-btn @click="saludar">¡Hola, Vuetify!</v-btn>
      </v-container>
    </v-main>
  </v-app>
</template>
<script>
export default {
  methods: {
    saludar() {
      alert('¡Hola, Vuetify!')
    }
  }
}
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
