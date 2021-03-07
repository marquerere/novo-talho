<template>
  <div class="flex flex-col justify-evenly">
    <div
      class="flex flex-col items-center justify-between px-8 py-8 xl:px-64 xl:flex-row "
    >
      <div
        class="flex flex-col items-center text-center xl:text-left xl:items-start"
      >
        <h1 class="text-4xl font-bold tracking-tight text-red-500 uppercase">
          Confie na carne que consome.
        </h1>
        <h2 class="pt-2 text-xl tracking-tight text-gray-400 uppercase">
          Escolha qualidade, sem abdicar do melhor preço.
        </h2>
        <button
          class="flex flex-row justify-center w-full px-8 py-4 mt-8 text-lg font-semibold text-center text-white uppercase transition bg-red-500 rounded hover:bg-red-700 sm:w-auto sm:text-left"
        >
          <i class="hidden pr-2 mdi mdi-cart sm:flex"></i>
          Encomendar Agora
        </button>
      </div>
      <div class="pt-8 xl:pt-0">
        <img src="../../public/images/meat.webp" alt="" />
      </div>
    </div>
    <section-splitter :icon="'mdi-knife'" />
    <div
      class="grid grid-cols-2 gap-8 py-8 mx-8 font-semibold text-gray-400 uppercase lg:grid-cols-4 xl:mx-64"
    >
      <div class="flex flex-col items-center ">
        <i class="pb-4 text-4xl text-red-500 mdi mdi-cart"></i>
        <span>1. Encomende</span>
      </div>
      <div class="flex flex-col items-center">
        <i class="pb-4 text-4xl text-red-500 mdi mdi-package"></i>
        <span>2. Receba</span>
      </div>
      <div class="flex flex-col items-center">
        <i class="pb-4 text-4xl text-red-500 mdi mdi-fire"></i>
        <span>3. Cozinhe</span>
      </div>
      <div class="flex flex-col items-center">
        <i class="pb-4 text-4xl text-red-500 mdi mdi-silverware-variant"></i>
        <span>4. Desfrute</span>
      </div>
    </div>
    <section-splitter :icon="'mdi-heart-box'" />
    <div
      class="flex flex-col items-center justify-between px-8 pt-8 xl:px-64 xl:flex-row "
    >
      <div class="pb-8 mx-auto xl:ml-0 xl:pb-0">
        <img src="../../public/images/reviews.webp" alt="" />
      </div>
      <div
        class="flex flex-col items-center pt-8 text-center xl:pt-0 xl:text-right xl:items-end"
      >
        <h1 class="text-4xl font-bold tracking-tight text-red-500 uppercase">
          Valorizamos a sua confiança.
        </h1>
        <h2 class="pt-2 text-xl tracking-tight text-gray-400 uppercase">
          Veja alguns testemunhos dos nossos clientes.
        </h2>
      </div>
    </div>
    <section-splitter :icon="'mdi-map-marker-radius'" />
  </div>
</template>

<script>
import SectionSplitter from "./SectionSplitter.vue";
export default {
  components: { SectionSplitter },
  name: "HeroSection",
};
</script>

<style>
.fullscreen {
  width: 100vw;
  height: calc(100vh - 149px);
}
</style>
