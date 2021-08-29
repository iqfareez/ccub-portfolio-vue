<template>
  <div class="body">
    <v-container class="px-md-12 py-8">
      <div class="text-h5">Hobby & Skills 💪🏼</div>
      <br />
      <div class="text-body-2">
        what fields you are expert in, what do you like to do, hobbies, etc.
      </div>
      <div class="text-body-2">I like to <b>build</b> something.</div>
      <div class="text-body-2">
        Here are few programming languages and tools that I know:
      </div>
      <br />
      <v-row>
        <v-img
          contain
          max-width="40"
          max-height="50"
          class="ma-3"
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
        "https://lh3.googleusercontent.com/pw/AM-JKLU8RSypASLbiF0ns50xuz9MwEHZL1phjyfG93GUOyJ30xc4JlRH83nTfJJ3FjkAY7yUzX7KCwHXZfMXN-Mm5ICwewc0Ox2c3797Q5Cf3fx5LWjqeqXFki106P7qtUu3cwH7JP8rFCT4RNW_moNJt_3x5A=w1281-h855-no",
        "secondary",
        "yellow darken-2",
        "red",
        "orange",
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

