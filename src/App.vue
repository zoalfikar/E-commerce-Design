<template>
<v-app>
  <Navebar class="index"/>
  <Dash-board/>
  <Foote-r />

</v-app>
</template>

<script>
import DashBoard from './components/Dash-board.vue';
import Navebar from './components/Nave-bare.vue';
import FooteR from './components/Footer-bare.vue';

export default {
  name: 'App',

  components: {

    DashBoard,
    FooteR,
    Navebar,
  },

  data: () => ({
    //
  }),
};
</script>
<style scoped>
.index {
  z-index: 999;
}
</style>
