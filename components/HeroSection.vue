<template>
  <div class="flex justify-between relative flex-col lg:flex-row">
    <img
      src="../public/backgrounShade.png"
      class="z-[-30] absolute h-full bottom-10 w-full"
    />

    <div
      class="w-full lg:w-[50%] px-[1.5rem] lg:pr-0 lg:pl-[3rem] xl:pl-[4rem]"
    >
      <NavHeader />

      <div class="lg:mt-[6rem] xl:mt-[8rem] mt-[3.25rem]">
        <h1
          class="text-[2.25rem] lg:text-[4rem] xl:text-[4.4rem] leading-[2.25rem] lg:leading-[4rem] tracking-[0.02rem] text-[#4C1506]"
        >
          Decentralizing
        </h1>
        <h2
          class="text-[2.25rem] lg:text-[3.5rem] xl:text-[4.06rem] leading-[2.25rem] lg:leading-[4rem] tracking-[0.01px] lg:tracking-[0.16rem] text-[#4C1506]"
        >
          access to research
        </h2>

        <h2
          class="text-[2.25rem] lg:text-[3.5rem] xl:text-[4.06rem] leading-[2.25rem] lg:leading-[4rem] tracking-[0.01px] lg:tracking-[0.16rem] text-[#4C1506] relative"
        >
          <div
            class="bg-[#FDC22161] h-[15px] w-[125px] lg:w-[240px] absolute top-[25px] lg:top-[40px] left-[3px] z-[-5]"
          ></div>
          in Africa
        </h2>

        <p
          class="text-[#331B3BA8] text-[1.06rem] leading-[1.5rem] md:leading-[1.6rem] ltracking-[0.5px] g:tracking-[0.34px] mt-[1.75rem] md:mt-[2.5rem] lg:w-[80%] "
        >
          We are bridging the gap by connecting researchers to millions of
          Africans eligible for these studies. Through a direct-to-patient
          approach, our goal is to decentralize clinical trials through a
          unified platform.
        </p>

        <a
          class="underline flex text-[#D86E23] items-center mt-[1.5rem] md:mt-[1rem] cursor-pointer"
        >
          <p
            class="text-[#D86E23] text-[1.06rem] leading-[1.6rem] tracking-[0.34px]"
          >
            Find out more on our website
          </p>
          <img src="/arrow-right-up.svg" />
        </a>
      </div>
    </div>
    <div class="mt-[6rem] lg:mt-0 flex w-full xl:w-[50%]  justify-end">
      <img src="/heroImage.png" class="w-[80%] lg:w-full" />
    </div>
  </div>
</template>

<script>
import NavHeader from "@/components/NavHeader.vue";

export default {
  components: {
    NavHeader,
  },
};
</script>

<style scoped>
h1 {
  font-family: Hind Vadodara;
  font-weight: 900;
}

h2 {
  font-family: Hind Vadodara;
  font-weight: 100;
}

p {
  font-family: Inter;
  font-weight: 400;
}
</style>
