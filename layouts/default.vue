<template>
  <Fragment>
    <NavBar/>
    <Nuxt/>
  </Fragment>
</template>
<script>
import {Fragment} from 'vue-fragment';

export default {
  components: { Fragment },
  layout: 'default',
  
}
</script>
<style lang="scss" scoped>
  div {
    float: left;
    left: 0;
    right: 0;
    top: 0;
    position: fixed;
  }
  .main__container {
    display: flex;
  }
</style>