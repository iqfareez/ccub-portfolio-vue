<template>
  <v-app id="inspire">
    <v-main class="grey lighten-3">
      <v-container>
        <div class="text-overline text--secondary">E-PORTFOLIO USRAH BUDI</div>
      </v-container>
      <v-container>
        <v-row>
          <v-col cols="12" md="4"> <ProfileCard /> </v-col>

          <v-col cols="12" md="8">
            <v-sheet min-height="100vh" rounded="lg">
              <Biodata />
              <Skills />
              <Contribution />
              <Activities />
            </v-sheet>
            <Footer />
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Biodata from "./Biodata.vue";
import Skills from "./Skills.vue";
import Contribution from "./Contribution.vue";
import Activities from "./Activities.vue";
import Footer from "./footer.vue";
import ProfileCard from "./ProfileCard.vue";

export default {
  name: "MyPage",
  components: {
    ProfileCard,
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