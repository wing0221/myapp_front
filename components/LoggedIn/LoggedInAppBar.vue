<template>
  <v-app-bar
    app
    dense
    elevation="1"
    clipped-left
    color="white"
  >
    <nuxt-link
      to="redirectPath"
      class="text-decoration-none"
    >
      <app-logo />
    </nuxt-link>

    <app-title />
    <v-spacer />
    <before-login-app-signup-button />
    <before-login-app-login-button />
    <logged-in-app-bar-account-menu />
  </v-app-bar>
</template>

<script>
export default {
}
</script>
