<template>
  <div
    class="flex flex-col lg:flex-row items-center justify-between mt-[8rem] mb-[4rem] px-[1.5rem] lg:pl-[6rem] lg:pr-[4rem] "
  >
    <img
      src="/logo.svg"
      class="w-[174px] h-[54px] cursor-pointer mb-[1.5rem] lg:mb-0"
    />
    <div class="flex flex-col lg:flex-row xl:space-x-[5rem] lg:space-x-[3rem] ">
      <div
        class="flex flex-col space-y-[2.5rem] lg:space-y-0 lg:flex-row items-center lg:space-x-[1rem] xl:space-x-[2rem]"
      >
        <h1
          class="text-[#4F5059] text-[1.125rem] tracking-[-0.5px] leading-[1.75rem] cursor-pointer"
        >
          Support
        </h1>
        <h1
          class="leading-[1.4rem] cursor-pointer text-[1.125rem] leading-[1.75rem] cursor-pointer text-[#4F5059]"
        >
          Privacy Policy
        </h1>
        <h1
          class="leading-[1.4rem] text-[1.125rem] text-[#4F5059] leading-[1.75rem] cursor-pointer"
        >
          Terms and Conditions
        </h1>
      </div>
      <h2
        class="text-[#4F5059] leading-[2.25rem] text-[1rem] tracking-[-0.5px] mt-[2.5rem] lg:mt-0"
      >
        © 2022 Infiuss Health, All Rights Reserved
      </h2>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1 {
  font-family: Inter;
  font-weight: 600;
}

@media (min-width: 1024px) {
  h1 {
    font-family: Inter;
    font-weight: 400;
  }
}

h2 {
  font-family: Inter;
  font-weight: 300;
}
</style>
