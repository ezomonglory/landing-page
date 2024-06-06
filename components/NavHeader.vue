<template>
  <div
    class="flex justify-between lg:justify-start items-center lg:spaxe-x-[2.5rem] xl:space-x-[3.25rem] mt-[2rem]"
  >
    <img src="/logo.svg" class=" ml-[-20px]  w-[174px] h-[54px] cursor-pointer" />
    <div
      class="items-center lg:space-x-[1rem] xl:space-x-[2.5rem] hidden lg:flex"
    >
      <h1
        class="text-[#F59E0B] text-[1.125rem] tracking-[-0.5px] leading-[1.4rem] cursor-pointer"
      >
        Home
      </h1>
      <h2
        class="leading-[1.4rem] cursor-pointer text-[1.125rem] cursor-pointer text-[#1B1B1BB2]"
      >
        Why Us?
      </h2>
      <h2
        class="leading-[1.4rem] text-[1.125rem] text-[#1B1B1BB2] cursor-pointer"
      >
        Why You?
      </h2>
    </div>

    <div class="lg:hidden">
      <img src="/navBar.svg" />
    </div>
  </div>
</template>

<script>
export default { 
  components: {},
};
</script>

<style scoped>
h1 {
  font-family: Inter;
  font-weight: 600;
}

h2 {
  font-family: Inter;
  font-weight: 400;
}
</style>
