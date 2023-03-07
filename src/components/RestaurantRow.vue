<template>
    <div class="restaurant--row">
        <h2 class="title">
            Nos restaurants
        </h2>
        <div class="wrapper-content">
            <restaurant-card v-for="(card, index) in 3" :key="index" />
        </div>
    </div>
</template>

<script>
import RestaurantCard from './RestaurantCard.vue'
export default {
    components: { RestaurantCard },
    name: "RestaurantRow"
}
</script>

<style lang="scss">
.wrapper-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
</style>