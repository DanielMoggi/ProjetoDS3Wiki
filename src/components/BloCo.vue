<script>
export default {
  props: {
    imagem: { type: String },
  },
};
</script>
<template>
  <article class="block">
    <hr />
    <img :src="imagem" width="220" height="220" />
  </article>
</template>
<style></style>
