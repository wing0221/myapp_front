<template>
  <v-container>
    <!-- chapter68出来ず -->
    <nuxt-child />
  </v-container>
</template>

<script>
export default {
  layout: 'project',
  validate ({ store, route }) {
    return !!store.state.project.current && route.name !== 'project'
  },
  data () {
    return {
      dashboardPath: 'project-id-dashboard'
    }
  },
  computed: {
    currentProject () {
      return this.store.state.project.current
    }
  }
}
</script>
