<template>
    <div class="links">
        <RouterLink to="/" active-class="active">Home</RouterLink>
        <RouterLink to="/about" active-class="active">About</RouterLink>
    </div>
  <RouterView />
</template>


<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>


<style scoped>
.active {
  color: green
}
</style>