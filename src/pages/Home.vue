<template>
  <div id="app">
    <h1>VueJs Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
// @ is an alias to /src
import Calculator from "@/components/main/Calculator.vue";

export default {
  components: {
    Calculator,
  },
};
</script>

<style lang="scss" scoped>
#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100vh;
  color: #fff;
  background: linear-gradient(rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>
