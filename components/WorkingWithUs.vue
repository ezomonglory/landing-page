<template>
  <div class="px-[2rem] lg:px-[7rem] mt-[4.25rem] lg:mt-[8.25rem]">
    <div class="flex sm:items-center flex-col">
      <h1
        class="text-[#4C1506] text-[2.25rem] lg:text-[3.2rem] leading-[2.5rem] lg:leading-[4.6rem]"
      >
        Why you should Consider Working With us
      </h1>
      <p
        class="text-[1.12rem] text-[#5E6282] leading-[1.3rem] mt-[1rem] md:mt-0"
      >
        We’re currently in three african <br class="sm:hidden" />
        countries and we are constantly <br class="sm:hidden" />
        expanding.
      </p>
    </div>

    <div
      class="flex flex-col px-[1.5rem] lg:flex-row items-start justify-between space-y-[5rem] lg:space-y-0 lg:space-x-[2rem] mt-[3.62rem]"
    >
      <WorkingWithUsCard
        v-for="(item, index) in dataArray"
        :key="index"
        :imageUrl="item.imageSrc"
        :header="item.headerText"
        :text="item.descriptionText"
      />
    </div>
  </div>
</template>

<script>
import WorkingWithUsCard from "@/components/WorkingWithUsCard.vue";

export default {
  components: {
    WorkingWithUsCard,
  },

  data() {
    return {
      dataArray: [
        {
          imageSrc: "/work1.png",
          headerText: "Collaborate internationally",
          descriptionText:
            "Connect and collaborate internationally with sites and teams in South Africa, Cameroon, and Nigeria",
        },
        {
          imageSrc: "/work2.png",
          headerText: "Own your space",
          descriptionText:
            "Grow your skills with an intimate team where there is always room to participate and grow.",
        },
        {
          imageSrc: "/work3.png",
          headerText: "Make an impact",
          descriptionText:
            "At Infuiss, we are bringing rise to clinical research in Africa with over 5,000 recruited participants.",
        },
      ],
    };
  },
};
</script>

<style scoped>
h1 {
  font-family: Hind Vadodara;
  font-weight: 700;
}

p {
  font-family: Inter;
  font-weight: 400;
}
</style>
