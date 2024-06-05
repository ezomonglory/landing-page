<template>
  <div class="flex flex-col space-y-[1rem]">
    <h2 class=" text-[1.125rem] lg:text-[1.5rem] leading-[2.2rem] text-[#4C1506]">{{ header }}</h2>
    <input
      class="border border-[#C8C8C8] p-1 outline-none w-full rounded-[8px] h-[56px]"
    />
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
  font-family: Hind Vadodara;
  font-weight: 600;
}

p {
  font-family: Inter;
  font-weight: 400;
}
</style>
