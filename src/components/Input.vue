<template>
  <div id="div">
    <div id="div2">
      <div class="input-group">
        <input
          type="text"
          aria-label="Text input with segmented dropdown button"
        />
        <div class="input-group-append">
          <button type="button" class="btn btn-outline-secondary">
            Pesquisar
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
  
<script>
export default {
  name: "Input",
  data() {
    return {
      text: "",
    };
  },
};
</script>

<style scoped>
#div {
  display: flex;
  justify-content: center;
  align-items: center;
}

#div2{
  margin-top: 50px;
  border-radius: 5px;
  height: 50px;
  width: 450px;
  background: white;
  display: flex;
  justify-content: center;
}

.input-group {
  width: 100%;
}

.input-group input{
  width: 70%;
  border: transparent;
  outline: none;
  margin-left: 5px;
}

.input-group button{
  margin-left: 27px;
  margin-top: 3px;
  width: 100px;
  border: transparent;
  height: 45px;
  background: #411530c1;
  color: white;
}
</style>