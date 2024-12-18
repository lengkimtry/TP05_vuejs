
<template>
  <AppHeader />
  <div class="flex w-full  border ">

    <div class="flex flex-col justify-start border border-black">
      <div class="border ">Menu</div>
      <div class="page border ">
        <h1 class="text-black p-4 shadow-md border border-t-black">Section1</h1>
        <h1 class="text-black p-4 shadow-md border border-t-black">Section2</h1>
        <h1 class="text-black p-4 shadow-md border border-t-black">Section3</h1>
        <h1 class="text-black p-4 shadow-md border border-t-black">Section4</h1>
      </div>
    </div>


    <div class="flex items-center justify-center  w-full h-[255px] border border-y-black border-r-black">
      Welcome to page 1
    </div>
  </div>
</template>

<script>
import AppHeader from "@/components/header.vue";

export default {
  name: "Page1",
  component: AppHeader,
};
</script>

<style scoped>
.page {
  text-align: center;
}
</style>
