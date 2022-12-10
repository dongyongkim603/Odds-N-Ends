<template>
  <header class="navigation">
    <ul>
      header
    </ul>
  </header>
</template>
  
  <script>
  export default {
    name: 'NavBar',
    props: {

    },
    methods: {

    }
  }
  </script>
  
<style lang="scss" scoped>
  .navigation {
    position: fixed;
    float: left;
    left: 0;
    right: 0;
    top: 0;
    border: 1px solid #121314;
    border-top: 1px solid #2b2e30;
    border-radius: 5px;
    overflow: hidden;
    width:100%;
    height: 4rem;
    background-color: aqua;
  }
</style>