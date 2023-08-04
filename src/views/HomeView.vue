<template>
  <v-app>
    <NavbarComponent class="index" />
    <DashboardComponent />
    <FooterComponent />
  </v-app>
</template>

<script>
  import NavbarComponent from '../components/NavbarComponent.vue'
  import DashboardComponent from '../components/DashboardComponent.vue'
  import FooterComponent from '../components/FooterComponent.vue'

  export default {
    name: 'HomeView',

    components: {
      NavbarComponent,
      DashboardComponent,
      FooterComponent

    },
  }
</script>
<style scoped>
.index{
  z-index: 9999;
}
</style>