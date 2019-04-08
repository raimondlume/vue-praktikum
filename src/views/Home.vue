<template>
  <div class="home">
    <div class="title-bar">
      <h1>Food app</h1>
      <button>Eesti</button>
      <button>English</button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import FoodCard from '@/components/FoodCard.vue'
import { FoodItems } from "@/data/fooditems";

export default {
  name: 'home',
  components: {
    FoodCard
  },
  data () {
    return {
      foodItems: FoodItems
    }
  }
}
</script>
