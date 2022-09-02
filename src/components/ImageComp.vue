<template>
  <img
    class="container__image"
    :src="require('../assets/' + url)"
    alt="Qr Code Image"
  />
</template>

<script>
export default {
  name: "ImageComp",
  props: ["url"],
};
</script>
