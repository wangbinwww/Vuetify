<template>
  <v-app>
    <v-toolbar app dark class="indigo">
      <v-toolbar-title class="headline text-uppercase">
        <span>ICONICS</span>
        <span class="font-weight-light">很好的脚手架工具</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat href="https://iconics.com/Site/About/About.aspx" target="_blank">
        <span class="mr-2">关于ICONICS</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      //
    };
  }
};
</script>
