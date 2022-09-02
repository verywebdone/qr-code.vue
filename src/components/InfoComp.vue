<template>
  <div class="container__info">
    <h1>{{ Info[0] }}</h1>
    <p>
      {{ Info[1] }}
    </p>
  </div>
</template>

<script>
export default {
  name: "InfoComp",
  props: ["Info"],
};
</script>
