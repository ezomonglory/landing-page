<template>
  <div class=" px-[2rem] lg:px-[4rem] mt-[6rem]">
    <div class="flex flex-col lg:flex-row lg:items-center justify-between mb-[2rem]">
      <div class="">
        <h1
          class="text-[#4C1506] text-[2rem] text-left md:text-[3rem] leading-[2rem] md:leading-[3.2rem] tracking-[-0.48px]"
        >
          What We Offer
        </h1>
        <h2
          class="text-[#4C1506] text-[2rem] text-left md:text-[3rem] leading-[2rem] md:leading-[3.2rem] tracking-[-0.48px] relative w-fit "
        >
          To Our Clients

          <!-- this is the yellowish vector below the our client txext -->
          <div
            class="bg-[#FDC22161] h-[7px] w-[125px] md:w-[200px] lg:w-[215px] absolute md:right-[0px] md:top-[35px]  top-[25px] lg:top-[35px] right-[0px] lg:right-[0px] z-[-5]"
          ></div>
        </h2>
      </div>

      <p
        class="text-[#5E6282] text-[1.06rem] leading-[1.4rem] lg:leading-[1.6rem] tracking-[] md:w-[37%] mt-[1.25rem] lg:mt-0 "
      >
        Watch this one minute video so you understand our journey, our story,
        and where we are headed!
      </p>
    </div>

    <img src="/offersImage.png" class="w-full" />

    <div class="flex flex-col items-center mt-[2rem] lg:mt-[4.3rem]">
      <p class="text-[#212121] text-[0.825rem] lg:text-[1.125rem] lg:leading-[1.125rem]">
        Want to read more?
      </p>
      <a class="flex items-center cursor-pointer space-x-[6px]">
        <h3 class="text-[#F59E0B] text-[1rem] lg:text-[1.4rem] lg:leading-[2rem]">
          Explore all Infiuss Health products
        </h3>
        <img src="/chevron-right.svg" />
      </a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1 {
  font-family: Hind Vadodara;
  font-weight: 700;
}

h2 {
  font-family: Hind Vadodara;
  font-weight: 300;
}

h3 {
  font-family: Hind Vadodara;
  font-weight: 400;
}

p {
  font-family: Inter;
  font-weight: 400;
}
</style>
