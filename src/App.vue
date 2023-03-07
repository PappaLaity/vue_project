<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div>

    <restaurant-row />
    <!-- <restaurant-row /> -->

  </div>
</template>

<script>
import RestaurantRow from "./components/RestaurantRow.vue"
export default {
  name: 'App',
  components: {
    RestaurantRow
  }
}
</script>

<style>
@import url('./styles/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@100&display=swap');

#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  padding: 10px;
  /* margin-top: 60px; */
}
</style>
