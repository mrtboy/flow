<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Flow</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        href="http://www.draw2d.org/draw2d/"
        target="_blank"
      >
        <span class="mr-2">Based on</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <Workspace/>
    </v-content>
  </v-app>
</template>

<script>
import Workspace from './components/Workspace.vue';

export default {
  name: 'App',
  components: {
    Workspace,
  },
  data() {
    return {
      //
    };
  },
};
</script>
