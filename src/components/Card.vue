<template>
  <div class="card" style="width: 18rem; height: 350px;">
    <div class="card-body">
      <h2 class="card-title">Maputo</h2>
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk
        of the card's content.
      </p>
      <div id="graus">
        <h4> 20 C</h4>
        <h4> 20 C</h4>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
};
</script>

<style scoped>
.card{
    background: #4E3863;
    color: white;
}

h2{
    text-align: center;
}

#graus{
    font-style: italic;
    margin-top: 160px;
    display: flex;
    width: 100%;
    justify-content: space-between;

}
</style>