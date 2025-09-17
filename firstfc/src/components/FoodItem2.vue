<template>
  <div class="food-box pizza">
    <h3>🍕</h3>
    <p>I love pizza as well!!</p>
  </div>
</template>

<script>
export default {
  name: "FoodItem2"
}
</script>

<style scoped>
.food-box {
  border-radius: 12px;
  padding: 15px;
  margin: 10px 0;
  max-width: 250px;
  font-family: 'Poppins', sans-serif;
  box-shadow: 2px 2px 6px rgba(0,0,0,0.15);
}
.pizza {
  background-color: #fff176; /* light yellow */
  color: #2c2c2c;
}
.food-box h3 {
  margin: 0 0 8px 0;
}
</style>
