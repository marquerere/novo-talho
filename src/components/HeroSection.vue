<template>
  <div class="flex flex-col justify-evenly">
    <div
      class="flex flex-col items-center justify-between px-16 py-8 xl:px-64 xl:flex-row "
    >
      <div class="flex flex-col items-center xl:items-start">
        <span class="text-4xl font-bold tracking-tight uppercase">
          Confie na carne que consome.
        </span>
        <span class="pt-2 text-xl tracking-tight text-gray-400 uppercase">
          Escolha qualidade, sem abdicar do melhor preço.
        </span>
        <button
          class="inline-flex px-8 py-4 mt-8 text-lg font-semibold text-white uppercase transition bg-red-500 rounded hover:bg-red-700"
        >
          <i class="hidden pr-2 mdi mdi-cart sm:flex"></i>
          Encomendar Agora
        </button>
      </div>
      <div class="pt-8 xl:pt-0">
        <img src="../../public/images/meat.png" alt="" />
      </div>
    </div>
    <div class="flex flex-row items-center mx-16 xl:mx-64">
      <hr class="flex-1 border-gray-200" />
      <div class="ml-8 text-center text-gray-400 lg:mx-8">
        <i class="text-xl mdi mdi-knife"></i>
      </div>
      <hr class="flex-1 hidden border-gray-200 lg:flex" />
    </div>
    <div class="py-8 mx-16 xl:mx-64">
      <div class="flex flex-col w-full pb-8 text-center">
        <span class="text-lg font-bold tracking-wide uppercase"
          >Entrega ao domicílio</span
        >
        <span class="pt-2 text-xs font-semibold text-gray-400 uppercase"
          >Conheça os 4 passos do nosso processo</span
        >
      </div>
      <div
        class="flex flex-col items-center justify-between space-y-10 font-semibold text-gray-500 uppercase lg:space-y-0 lg:items-center lg:flex-row text"
      >
        <div class="flex flex-col items-center lg:flex-row">
          <i class="text-4xl text-red-500 lg:pr-8 mdi mdi-cart"></i>
          <span>Encomende</span>
        </div>
        <div class="flex flex-col items-center lg:flex-row">
          <i class="text-4xl text-red-500 lg:pr-8 mdi mdi-package"></i>
          <span>Receba</span>
        </div>
        <div class="flex flex-col items-center lg:flex-row">
          <i class="text-4xl text-red-500 lg:pr-8 mdi mdi-fire"></i>
          <span>Cozinhe</span>
        </div>
        <div class="flex flex-col items-center lg:flex-row">
          <i
            class="text-4xl text-red-500 lg:pr-8 mdi mdi-silverware-variant"
          ></i>
          <span>Desfrute</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style>
.fullscreen {
  width: 100vw;
  height: calc(100vh - 149px);
}
</style>
