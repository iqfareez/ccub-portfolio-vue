<template>
  <div class="body">
    <v-container class="px-md-12 py-8">
      <div class="text-h5">Contribution 💁🏼‍♂️</div>
      <br />
      <div class="row">
        <v-card @click="openInstagram" class="mx-auto my-2" max-width="300">
          <v-img
            src="@/assets/1640332725930-crop (Custom).jpg"
            max-height="180"
          ></v-img>
          <v-card-title
            ><i class="fas fa-people-carry"></i> &nbsp;SCUBA
            Harmoni</v-card-title
          >
          <v-card-subtitle
            >Flood relief volunteer at Hulu Langat.
            #daruratbanjir</v-card-subtitle
          >
        </v-card>
        <v-card @click="openWordpress" class="mx-auto my-2" max-width="300">
          <v-img
            src="https://neilpatel.com/wp-content/uploads/2018/10/blog.jpg"
            max-height="180"
          ></v-img>
          <v-card-title
            ><i class="fab fa-wordpress"></i> &nbsp;Blog (est.
            2014)</v-card-title
          >
          <v-card-subtitle
            >I shared some tazkirah collected from articles and
            speeches.</v-card-subtitle
          >
        </v-card>
        <v-card @click="openYoutube" class="mx-auto my-2" max-width="300">
          <iframe
            width="300"
            height="180"
            src="https://www.youtube.com/embed/fnrjo_rnh44"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          >
          </iframe>
          <v-card-title
            ><i class="fab fa-youtube"></i> &nbsp;YouTube</v-card-title
          >
          <v-card-subtitle
            >Related Islamic videos also can be find on the
            channel</v-card-subtitle
          >
        </v-card>
        <v-card @click="openMpt" class="mx-auto my-2" max-width="300">
          <v-img src="@/assets/mpt_promo.png" height="180"></v-img>
          <v-card-title
            ><i class="fab fa-google-play"></i> &nbsp;Malaysia Prayer
            Time</v-card-title
          >
          <v-card-subtitle
            >Prayer Time app available for Android and the web.</v-card-subtitle
          >
        </v-card>
      </div>
    </v-container>

    <!-- <v-parallax height="200" src="@/assets/bgori.jpeg"></v-parallax> -->
  </div>
</template>



<script>
export default {
  name: "Contribution",
  methods: {
    openYoutube: function () {
      window.open("https://www.youtube.com/channel/UCQMzHPj_FXS5t2_ei8JjMSA");
    },
    openInstagram: function () {
      window.open("https://www.instagram.com/ingatdakwah.wordpress/");
    },
    openWordpress: function () {
      window.open("https://ingatdakwah.wordpress.com/");
    },
    openMpt: function () {
      window.open(
        "https://play.google.com/store/apps/details?id=live.iqfareez.waktusolatmalaysia"
      );
    },
  },
};
</script>



<style scoped>
.fa-youtube {
  color: rgb(255, 0, 0);
}

.fa-people-carry {
  color: #c13584;
}

.fa-wordpress {
  color: #0073aa;
}

.fa-google-play {
  color: #00ceff;
}
</style>