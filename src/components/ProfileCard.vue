<template>
  <div class="d-flex flex-column">
    <v-sheet
      fill-height
      align="center"
      justify="center"
      class="justify-center"
      rounded="lg"
      style="padding: 20px 20px"
    >
      <v-img
        class="rounded-circle"
        lazy-src="https://picsum.photos/16/16"
        max-height="100"
        max-width="100"
        src="@/assets/20191003_145839_squared.jpg"
      ></v-img>
      <br />
      <div class="text-body-1">Muhammad Fareez Iqmal<br /></div>
      <div class="text-subtitle-2 font-weight-light">1914577 | CCUB 4621</div>
    </v-sheet>
  </div>
</template>

<script>
export default {
  name: "ProfileCard",
};
</script>