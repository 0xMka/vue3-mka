<template>
  <div id="app">
    <RestaurantCard/>
  </div>
</template>

<script>
import RestaurantCard from './components/RestaurantCard.vue'
export default {
  name: 'App',
  components: {
    RestaurantCard
  }
}
</script>

<style>
@import url('./style/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');
#app {
  font-family: 'Roboto', sans-serif;
}
</style>
