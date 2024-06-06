<template>
  <div class="px-[2rem] lg:px-[4.5rem] mt-[6.5rem] lg:mt-[11.3rem]">
    <div
      class="bg-[#4C1506] flex flex-col-reverse lg:flex-row p-[1.5rem] items-center justify-between rounded-[15px]"
    >
      <div class="lg:w-[47%] mt-[3rem] lg:mt-0">
        <h1
          class="text-[1.5rem] lg:text-[2.5rem] text-white racking-[0.1rem] leading-[1.7rem] lg:leading-[3rem] mb-[1.25rem]"
        >
          We are currently not hiring but are always looking for the best
          talent!
        </h1>

        <!-- This is the text for web view -->
        <h2
          class="text-[1.125rem] leading-[1.75rem] text-white hidden lg:block"
        >
          We refuse to miss out on the best of the best. We’re open to
          suggestions about why you’ll be a great addition to our team.
        </h2>

        <!-- This is the text for mobile view -->
        <h2 class="text-[1.125rem] leading-[1.75rem] text-white lg:hidden">
          We are currently not hiring but we refuse to miss out on the best of
          the best. We’re open to suggestions about why you’ll be a great
          addition to our team.
        </h2>
      </div>
      <div class="lg:w-[45%] flex justify-end">
        <img src="/hiring.png" />
      </div>
    </div>

    <div class="mt-[4rem] lg:px-[2.5rem]">
      <div class="flex flex-col space-y-[2.5rem]">
        <InputText
          v-for="(item, index) in inputData"
          :key="index"
          :header="item"
        />
      </div>

      <div class="mt-[2.625rem] flex flex-col lg:flex-row lg:space-x-[6.25rem]">
        <div>
          <h3
            class="text-[1.25rem] lg:text-[1.5rem] leading-[2.2rem] text-[#4C1506] mb-[2rem]"
          >
            Is your feedback a...
          </h3>
          <div class="flex flex-col space-y-[1.5rem]">
            <CheckBox
              v-for="(item, index) in checkBoxData1"
              :key="index"
              :header="item"
            />
          </div>
        </div>

        <div>
          <h3
            class="text-[1.25rem] lg:text-[1.5rem] mt-[2.625rem] lg:mt-0 leading-[2.2rem] text-[#4C1506] mb-[2rem]"
          >
            Is your feedback based on a position for…
          </h3>
          <div class="flex flex-col space-y-[1.5rem]">
            <CheckBox
              v-for="(item, index) in checkBoxData2"
              :key="index"
              :header="item"
            />
          </div>
        </div>
      </div>

      <div class="mt-[2.5rem]">
        <h3
          class="text-[1.125rem] lg:text-[1.5rem] leading-[1.5rem] lg:leading-[2.2rem] text-[#4C1506] mb-[1rem] lg:mb-[2rem]"
        >
          Show us what you got. Tell us why you'll be a great addition to our
          team.
        </h3>

        <textarea
          class="border border-[#C8C8C8] rounded-[8px] w-full resize-none outline-none p-2"
          rows="7"
        >
        </textarea>
      </div>

      <div
        class="rounded-[4px] hidden bg-[#F59E0B] w-[200px] h-[60px] lg:flex items-center justify-center mt-[3.75rem]"
      >
        <p class=".btn text-white text-[1.25rem] leading-[1.5rem]">Send</p>
      </div>
    </div>
  </div>
</template>

<script>
import InputText from "@/components/InputText.vue";
export default {
  components: {
    InputText,
  },

  data() {
    return {
      inputData: ["Name", "Email"],
      checkBoxData1: [
        "New role suggestion for you",
        "A must have that we don’t have",
        "Other",
      ],
      checkBoxData2: ["Full-time", "Part-time", "Internship"],
    };
  },
};
</script>

<style scoped>
h1 {
  font-family: Inter;
  font-weight: 900;
}

h2 {
  font-family: Roboto;
  font-weight: 400;
}

h3 {
  font-family: Hind Vadodara;
  font-weight: 600;
}

.btn {
  font-family: Inter;
  font-weight: 700;
}
</style>
