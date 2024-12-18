
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


    <div class="flex items-center justify-center bg-blue-600 text-white w-full h-[255px] border border-black">
      Welcome to page 2
    </div>
  </div>
</template>

<script>
export default {
  name: "Page2",
};
</script>

<style scoped>
.page {
  text-align: center;

}
</style>
