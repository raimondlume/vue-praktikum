<template>
  <div class="food-card">
    <h1>{{ title }}</h1>
    <h2>{{ provider }}</h2>
    <span>{{ price }}</span>
  </div>
</template>

<script>
  export default {
    name: "FoodCard",
    props: {
      title: String,
      provider: String,
      price: String
    }
  }
</script>

<style scoped>

</style>
