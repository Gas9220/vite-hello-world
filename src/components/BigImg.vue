<script>
export default {
  data() {
    return {
      source: "src/assets/img.png"
    }
  }
}
</script>

<template>
  <img :src="source" alt="img">
</template>

<style scoped>
img {
    width: 60%;
    border: .1875rem solid rebeccapurple;
    border-radius: .625rem;
}
</style>