<template>
  <h1>Hello WEBPROG World! Im Chrisjan</h1>
  <h2>Food</h2>
  <FoodItem />
  <FoodItem2 /> 
</template>

<script>
import FoodItem from './components/FoodItem.vue'
import FoodItem2 from './components/FoodItem2.vue'

export default {
  name: "App",
  components: {
    FoodItem,
    FoodItem2
  }
}
</script>
