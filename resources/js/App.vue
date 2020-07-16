<template>
  <v-app>
    <v-app-bar color="deep-purple accent-4" max-height="7%" dense dark flat></v-app-bar>
    <v-container>
      <div>
        <example/>
      </div>
    </v-container>
  </v-app>
</template>

<script>
import example from "./components/ExampleComponent";
export default {
  components: {
    example
  },
  mounted() {
    console.log("Component mounted.");
  }
};
</script>
