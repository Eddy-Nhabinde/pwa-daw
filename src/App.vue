<template>
  <MainPage />
</template>

<script>
import MainPage from "./components/MainPage.vue";

export default {
  name: "App",
  components: {
    MainPage,
  },
};
</script>

<style>
body {
  height: 100vh;
  background: rgb(65, 21, 48);
  background: linear-gradient(
    -185deg,
    rgba(65, 21, 48, 1) 55%,
    rgba(255, 255, 255, 1) 55%
  );
}
</style>
