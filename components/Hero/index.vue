<template>
  <div class="hero__container">
    <img
      class="hero__image"
     :src="imageSource" />
  </div>
</template>
  
<script>
export default {
  name: 'Hero',
  props: {
      imageSource: String
  },
  data() {
    return {
      src: this.imageSource  
    }
  }
}
</script>
<style lang="scss" scoped>
  .hero__container {
    width: 100%;
    height: 100%;
  }

  .hero__image {
    width: 100%;
    height: auto;
  }
</style>
  