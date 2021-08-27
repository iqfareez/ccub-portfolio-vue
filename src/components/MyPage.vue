<template>
  <v-sheet min-height="100vh" rounded="lg">
    <Biodata />
    <Skills />
    <Contribution />
    <Activities />
  </v-sheet>
</template>

<script>
import Biodata from "./Biodata.vue";
import Skills from "./Skills.vue";
import Contribution from "./Contribution.vue";
import Activities from "./Activities.vue";

export default {
  name: "MyPage",
  components: {
    Biodata,
    Skills,
    Contribution,
    Activities,
  },
};
</script>

<style scoped>
</style>