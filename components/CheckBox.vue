<template>
  <div class="flex space-x-[1.5rem] items-center">
    <div class="w-[28px] h-[28px] border-[2px] border-[#4C1506] rounded-[4px] "></div>
    <h2 class="text-[1.125rem] leading-[1.25rem] text-[#4C1506B2]">
      {{ header }}
    </h2>
  </div>
</template>

<script>
export default {
  props: {
    header: String,
  },
};
</script>

<style scoped>
h2 {
  font-family: Inter;
  font-weight: 400;
}

p {
  font-family: Inter;
  font-weight: 400;
}
</style>
