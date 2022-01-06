<template>
  <v-app>
    <bafore-login-app-bar />
    <v-main>
      <nuxt />
    </v-main>
    <app-footer />>
  </v-app>
</template>

<script>
import BaforeLoginAppBar from '../components/BaforeLogin/BaforeLoginAppBar.vue'
import AppFooter from '../components/App/AppFooter.vue'
export default {
  components: { BaforeLoginAppBar, AppFooter }
}
</script>
