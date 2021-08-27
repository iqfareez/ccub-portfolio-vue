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
            <MyPage />
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import ProfileCard from "./components/ProfileCard.vue";
import MyPage from "./components/MyPage.vue";
export default {
  components: {
    ProfileCard,
    MyPage,
  },
  data: () => ({
    links: ["Dashboard", "Messages", "Profile", "Updates"],
  }),
};
</script>