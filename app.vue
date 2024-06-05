<template>
  <div>
    <HeroSection />
    <OfferSection />
    <WorkingWithUs />
    <Hiring />
    <Footer />
  </div>
</template>

<script>
import HeroSection from "@/components/HeroSection.vue";
import OfferSection from "@/components/OfferSection.vue";
import WorkingWithUs from "@/components/WorkingWithUs.vue";
import Hiring from "@/components/Hiring.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    HeroSection,
    OfferSection,
    WorkingWithUs,
    Hiring,
    Footer,
  },
};
</script>
