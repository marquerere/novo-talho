<template>
  <div class="flex flex-row items-center py-8 mx-8 xl:mx-64">
    <hr class="flex-1 border-gray-200" />
    <div class="ml-8 text-center text-gray-400 lg:mx-8">
      <i class="text-xl mdi" :class="icon"></i>
    </div>
    <hr class="flex-1 hidden border-gray-200 lg:flex" />
  </div>
</template>

<script>
export default {
  name: "SectionSplitter",
  props: {
    icon: { Type: String, required: false },
  },
};
</script>

<style></style>
