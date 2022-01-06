<template>
  <v-toolbar-title>
    {{ appName }}
  </v-toolbar-title>
</template>

<script>
export default {
  date ({ $config: { appName } }) {
    return {
      appName
    }
  }
}
</script>
