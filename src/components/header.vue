<template>
  <header
    class="text-white p-4 shadow-md w-[1024px] mx-auto border-t border-x border-black"
  >
    <div class="flex items-center justify-between">

      <div class="text-xl font-bold text-fuchsia-400">Header</div>


      <nav class="space-x-2">
        <router-link
          class="hover:underline text-black"
          to="page1"
          active-class="text-blue-500"
          exact-active-class="text-blue-700"
        >
          Go to Page 1
        </router-link>

        <router-link
          class="hover:underline text-black"
          to="page2"
          active-class="text-blue-500"
          exact-active-class="text-blue-700"
        >
          Go to Page 2
        </router-link>

        <router-link
          class="hover:underline text-black"
          to="page3"
          active-class="text-blue-500"
          exact-active-class="text-blue-700"
        >
          Go to Page 3
        </router-link>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>
