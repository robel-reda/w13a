<template>
  <div id="app">


<!-- Website Header -->
<HeaderComponent />

<!-- Main Website Body -->
<BodyComponent />

<!-- Website Footer -->
<FooterComponent />


  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue/index.js";
import BodyComponent from "./components/BodyComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";

export default {
  name: "App",

  components: {
    HeaderComponent,
    BodyComponent,
    FooterComponent
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
}
</style>
