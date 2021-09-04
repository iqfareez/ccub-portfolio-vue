<template>
  <div class="body">
    <v-container class="px-md-12 py-8">
      <div class="text-h5">Hobby & Skills 💪🏼</div>
      <br />
      <p>Nothing much, but I like to <b>build</b> something.</p>
      <p>Here are some side-projects that I made:</p>
      <v-carousel height="auto">
        <v-carousel-item
          contain
          :href="img.link"
          target="_blank"
          v-for="(img, index) in showcaseImages"
          :key="index"
          :src="img.src"
        >
          <v-row class="fill-height pl-6" align="end" justify="start">
            <div class="text-xs-h5 text-sm-h3 white--text pb-10">
              {{ img.title }}
            </div>
          </v-row>
        </v-carousel-item>
      </v-carousel>
      <br />
      <p>And here are few programming languages and tools that I know:</p>
      <br />
      <v-row>
        <v-img
          contain
          max-width="40"
          max-height="50"
          class="ml-3 mb-2"
          v-for="(logo, index) in logos"
          :alt="logo.imgAlt"
          :src="logo.imgSrc"
          :key="index"
        />
      </v-row>
    </v-container>
    <v-parallax
      height="200"
      src="https://lh3.googleusercontent.com/pw/AM-JKLU8RSypASLbiF0ns50xuz9MwEHZL1phjyfG93GUOyJ30xc4JlRH83nTfJJ3FjkAY7yUzX7KCwHXZfMXN-Mm5ICwewc0Ox2c3797Q5Cf3fx5LWjqeqXFki106P7qtUu3cwH7JP8rFCT4RNW_moNJt_3x5A=w1281-h855-no"
    ></v-parallax>
  </div>
</template>

<script>
export default {
  name: "Skills",
  data: function () {
    return {
      model: 0,
      showcaseImages: [
        {
          src: "https://lh3.googleusercontent.com/pw/AM-JKLUaNVHdSFBU1qsjqh7yTg36c4eNz216DlUYSE44Q1Xtf1DiaO5xgtW4etFb-TpSOE9SUHBv3VtfvlgLO1TJIJcJ-tyD7EVeWbOVtCUM4dHCWnj7TIX--jmbh_oI05tQGa_jEbjDqjitrFVG3pch3GFyPw=w1231-h923-no",
          title: "HuTem (IoT)",
          link: "https://github.com/iqfareez/PlatformIO-Projects/tree/main/DH11%20ESP%20Firebase",
        },
        {
          src: "https://lh3.googleusercontent.com/pw/AM-JKLV_5SHGwUp01Xfopis-1yGpgD481OYdpWwzGBgCjBCCp2wAr5Ntz7oH_DlazVZ65Ywaqj-hVFq6EwdhZqb3jTmSrHjRfgWS-kSX7RlfnpzBpyWVZ8ag1pzpID5vYDnN6tGheBPUKXYzddSqgAf92-TGaQ=w1231-h923-no",
          title: "Exam Timer",
          link: "https://github.com/iqfareez/PlatformIO-Projects/tree/main/Countdown%20Timer",
        },
      ],
      logos: [
        { imgSrc: require("@/assets/programminglogo/c.svg"), imgAlt: "C" },
        { imgSrc: require("@/assets/programminglogo/cpp.png"), imgAlt: "C++" },
        {
          imgSrc: require("@/assets/programminglogo/csharp.png"),
          imgAlt: "C-Sharp (not C-hastag ya)",
        },
        {
          imgSrc: require("@/assets/programminglogo/dart.png"),
          imgAlt: "Dart",
        },
        {
          imgSrc: require("@/assets/programminglogo/flutter.png"),
          imgAlt: "Flutter",
        },
        {
          imgSrc: require("@/assets/programminglogo/arduino.png"),
          imgAlt: "Arduino/ESP32/Microbit etc.",
        },
        {
          imgSrc: require("@/assets/programminglogo/html.png"),
          imgAlt: "HTML (with a little CSS & JS)",
        },
        {
          imgSrc: require("@/assets/programminglogo/git.png"),
          imgAlt: "Git/Github",
        },
        {
          imgSrc: require("@/assets/programminglogo/python.png"),
          imgAlt: "Python (Micropython coming soon.)",
        },
        {
          imgSrc: require("@/assets/programminglogo/unity.svg"),
          imgAlt: "Unity",
        },
      ],
    };
  },
};
</script>

