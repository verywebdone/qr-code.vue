<template>
  <div class="likeBody">
    <div class="container">
      <ImageComp :url="[url]" />
      <InfoComp :Info="[title, paragraph]" />
    </div>
  </div>
</template>

<script>
import InfoComp from "./components/InfoComp.vue";
import ImageComp from "./components/ImageComp.vue";

export default {
  name: "App",
  components: {
    ImageComp,
    InfoComp,
  },
  data() {
    return {
      title: "Improve yout font-end skills by bulding projects",
      paragraph:
        "Scan the QR code to visit Frontend Mentor and take your coding skills to the next level",
      url: "image-qr-code.png",
    };
  },
};
</script>
