<template>
  <div>
    <v-app-bar flat color="grey">
      <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>

      <v-toolbar-title>Page title</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
    </v-app-bar>
    <v-navigation-drawer app v-model="drawer" temporary>
      <v-layout mt-5 column align-center>
        <v-flex>
          <v-avatar>
            
          </v-avatar>
        </v-flex>
        <v-flex>
          <p>Rigoberto Urdaneta</p>
        </v-flex>
      </v-layout>
    </v-navigation-drawer>
  </div>
</template>

<script>

export default {
  name: "ToolBar",

  data: () => ({
    drawer: false,
    group: null,
  }),

  watch: {
    group() {
      this.drawer = false;
    },
  },
};
</script>

<style lang="scss" scoped>
@import "./scss/StyleBar.scss";
</style>
