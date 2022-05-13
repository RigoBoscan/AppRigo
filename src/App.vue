<template>
  <v-app>
    <ToolBar />
    <MainApp />
    <FooterApp />
  </v-app>
</template>

<script>
import ToolBar from "./components/ToolBar.vue";
import MainApp from "./components/MainApp.vue";
import FooterApp from "./components/FooterApp.vue";

export default {
  name: "App",

  components: {
    ToolBar,
    MainApp,
    FooterApp,
  },

  data: () => ({
    //
  }),
};
</script>
