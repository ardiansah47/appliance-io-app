<template>
  <v-app id="app">
    <router-link to="/">Home</router-link>
    <router-link to="/about">Go to About</router-link>
    <Button />
    <router-view></router-view>
  </v-app>
</template>

<script>
import Button from 'ui/components/Button.vue'
import {VApp} from 'vuetify/lib'
export default {
  name: 'App',
  components: {
    Button,
    VApp
  }
}
</script>