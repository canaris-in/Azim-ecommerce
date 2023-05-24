<template>
  <v-app>
    <NavebarView class="index" />
    <DashBoard />
    <FooterView />
  </v-app>
</template>

<script>
  import NavebarView from '../components/NavebarView'
  import DashBoard from '../components/DashBoard'
  import FooterView from '../components/FooterView'

  export default {
    name: 'HomeView',

    components: {
      NavebarView,
      DashBoard,
      FooterView

    },
  }
</script>
<style scoped>
.index{
  z-index: 9999;
}
</style>
