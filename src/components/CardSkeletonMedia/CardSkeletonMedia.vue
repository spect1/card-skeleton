<template>
  <v-card-text class="card-skeleton__media" :style="`height:${height};width:${width};`"></v-card-text>
</template>

<script>
export default {
  //   name: "",
  props: ["height", "width"]
};
</script>

<style scoped>
.card-skeleton__media {
  background-color: grey;
  /* height: 200px; */
  width: auto;
}
</style>