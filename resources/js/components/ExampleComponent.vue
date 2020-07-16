<template>
  <div class="container">
    <v-row>
      <v-card
        @mouseenter="hover = true"
        @mouseleave="hover = false"
        outlined
        class="pa-5"
        width="100%"
      >
        <v-card-title>Example Component</v-card-title>
        <v-card-content>I'm an example component.</v-card-content>
      </v-card>
    </v-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      hover: false
    };
  },
  mounted() {
    console.log("Component mounted.");
  }
};
</script>
