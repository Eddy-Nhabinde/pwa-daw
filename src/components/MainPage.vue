<template>
  <SearchComponentVue />
  <div id="div">
    <Card />
    <Card />
    <Card />
  </div>
</template>

<script>
import SearchComponentVue from "./SearchComponent.vue";
import Card from "./Card.vue";
export default {
  name: "MainPage",
  components: {
    SearchComponentVue,
    Card,
  },
};
</script>


<style scoped>
#div {
  width: 100%;
  margin-top: 80px;
  display: flex;
  justify-content:space-evenly;
}
</style>