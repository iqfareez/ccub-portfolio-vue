<template>
  <div class="body">
    <v-container class="px-md-12 py-8">
      <div class="text-h5">A little about myself ✌🏼</div>
      <br />
      <p>
        I was born in Hospital Mentakab, Pahang (2000). Lived in Puchong,
        Selangor since 2003. I went to SMK Seksyen 18, Shah Alam and later moved
        to MJSC Kuala Kubu Bharu, Selangor. Currently studying in IIUM Gombak
        pursuing Bachelor of Engineering (Mechatronics).
      </p>
      <p>
        Just some facts about me: I like popia, and potatoes product. I also
        like cats.
      </p>
      <!-- <br /> -->
      <div class="text-body-2">Just some random quote:</div>
      <blockquote class="blockquote">
        Success is no accident. It is
        <b> hard work, perseverane, studying, sacrifice</b>, and most of all,
        <b>LOVE</b> what you're doing
      </blockquote>
    </v-container>
    <v-parallax
      class="d-sm-none"
      src="https://lh3.googleusercontent.com/pw/AM-JKLUGf8WxNP4ANv04FoxEu_P_lw_qXbi7xu0CS3fsPJi02C4v6bRdT_rJvxhMnOR_4pfw9kRnYAJZqlHilPz11bGuYx1bXJEXLNMHf1F3MHACUVelbwIQfKp0bKvxCgqJXh7_mBxtHRb8j4S2ZYv3OtU1BA=w520-h923-no"
      height="200"
    >
    </v-parallax>
    <v-parallax
      class="d-none d-sm-flex"
      contain
      height="200"
      src="https://lh3.googleusercontent.com/pw/AM-JKLVv_VHF127Hl10_G2rik_KgrBPdu4H_djyG4NeDmOY7IbYlzqHJEMNdNCHFwTGcjvnsgrOcig4wowJRHMU7sJXn6D5Z3RaVipqw3fdDiRnRXGAvfaeWVhPvDH6HpYcB78Qgy0RFfdxEZ-CyrxA33Dghmw=w1231-h923-no"
    ></v-parallax>
  </div>
</template>

<script>
export default {
  name: "Biodata",
};
</script>

<style scoped>
</style>