<script setup>
import { RouterView } from "vue-router"; // Removed unused RouterLink
import AppHeader from "@/components/header.vue"; // Corrected import path
import AppFooter from "@/components/footer.vue"; // Corrected import path
</script>

<template>
   <div class=" flex-col">
  <header class="bg-gray-100 d">

    <div class="">
      <AppHeader />
    </div>
  </header>
 
        <RouterView />
    <div>
      <AppFooter />
    </div>
  </div>

</template>

<style scoped>
.wrapper {
  padding: 10px;
}
</style>
