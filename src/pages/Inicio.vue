<template>
  <div class="inicio">
    <button @click="load" class="inicio__button">
      <h1>Vue Calculator</h1>
      <h3>Clique Aqui</h3>
    </button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  components: {},
  methods: {
    load() {
      this.$router.push("/");
    },
  },
};
</script>

<style lang="scss" scoped>
.inicio {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100vh;
  color: #fff;
  background: linear-gradient(rgb(83, 105, 118), rgb(41, 46, 73));
  &__button {
    height: 400px;
    width: 400px;
    border-radius: 50%;
    border: 5px solid #fff;
    cursor: pointer;
    outline: none;
    background-color: #3acbc7;
    box-shadow: inset 0 0 1em white, 0 0 1em black;
    transition: 1s;
    h1 {
      font-size: 24px;
      color: #fff;
    }
    h3 {
      color: #fff;
    }
  }
}
</style>
