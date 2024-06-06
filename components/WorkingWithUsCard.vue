<template>
  <div class="flex flex-col relative w-fit">
    <img
      v-if="shouldDisplayImage"
      src="/spring.png"
      class="absolute right-[-20px] lg:right-[-50px] top-[35%] z-[-10]"
    />

    <div
      class="bg-image w-full h-[326px] rounded-t-[24px]"
      :style="{ backgroundImage: 'url(' + imageUrl + ')' }"
    ></div>

    <div
      class="p-[1.25rem] bg-[#FFFFFF] shadow-md shadow-gray-100 rounded-b-[24px]"
    >
      <h2 class="text-[1.25rem] leading-[1.5rem] text-[#5E6282] mt-[1rem]">
        {{ header }}
      </h2>
      <div class="flex items-start space-x-[0.825rem] mt-[1rem]">
        <img src="/arrow.svg" />
        <p class="text-[1.12rem] leading-[1.5rem] text-[#777A99]">
          {{ text }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    imageUrl: String,
    header: String,
    text: String,
  },

  computed: {
    shouldDisplayImage() {
      return this.header === "Make an impact";
    },
  },
};
</script>

<style scoped>
.bg-image {
  background-position: cover;
  background-size: cover;
}

h2 {
  font-family: Inter;
  font-weight: 500;
}

p {
  font-family: Inter;
  font-weight: 400;
}
</style>
