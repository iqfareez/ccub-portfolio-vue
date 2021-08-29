<template>
  <v-sheet min-height="100vh" rounded="lg">
    <Biodata />
    <Skills />
    <Contribution />
    <Activities />
    <Footer />
  </v-sheet>
</template>

<script>
import Biodata from "./Biodata.vue";
import Skills from "./Skills.vue";
import Contribution from "./Contribution.vue";
import Activities from "./Activities.vue";
import Footer from "./footer.vue";

export default {
  name: "MyPage",
  components: {
    Biodata,
    Skills,
    Contribution,
    Activities,
    Footer,
  },
};
</script>

<style scoped>
</style>