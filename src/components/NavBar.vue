<template>
  <header>
    <!-- <div
      class="items-center justify-between hidden w-full px-64 py-4 text-sm font-medium border-b border-gray-200 xl:flex"
    >
      <div v-for="(location, i) in locations" :key="i" class="space-x-4 ">
        <a
          :href="location.map"
          class="text-gray-400 transition-colors hover:text-black"
        >
          <i class="mdi mdi-map-marker" /> {{ location.address }}
        </a>
        <a
          :href="`tel:${location.phone}`"
          class="font-semibold text-red-500 transition-colors hover:text-red-700"
        >
          <i class="mdi mdi-phone" /> +{{ location.phone.replace("-", " ") }}
        </a>
      </div>
    </div> -->
    <nav class="flex items-center justify-between w-full px-16 py-8 xl:px-64">
      <div class="flex justify-center">
        <a href="" class="">
          <img class="h-12" src="../../public/images/logo.png" alt="" />
        </a>
      </div>

      <ul
        class="flex-row items-center justify-around hidden space-x-6 xl:space-x-12 xl:flex"
      >
        <li>
          <a href="" class="navLink">Sobre Nós</a>
        </li>
        <li>
          <a href="" class="navLink">Produtos</a>
        </li>
        <li>
          <a href="" class="navLink">Promoções</a>
        </li>
        <li>
          <a href="" class="navLink">Contactos</a>
        </li>
        <!-- <li>
          <a
            href=""
            class="flex items-center text-red-500 navLink hover:text-red-700"
          >
            Encomendar
            <i class="pl-2 text-xl mdi mdi-cart" />
          </a>
        </li> -->
      </ul>

      <div class="flex justify-center xl:hidden">
        <a href="#" class="">
          <i class="text-3xl mdi mdi-menu"></i>
        </a>
      </div>
    </nav>
  </header>
</template>

<script>
import locations from "../config/locations.json";
export default {
  name: "NavBar",
  data() {
    return {
      locations: locations,
    };
  },
};
</script>

<style>
.navLink {
  @apply font-bold;
  @apply text-gray-700;
  @apply text-sm;
  @apply uppercase;
  transition: all 0.2s;
}
.navLink:hover {
  @apply text-red-600;
}
</style>
