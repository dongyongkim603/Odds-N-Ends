<template>
    <img :src="imageSource" />
</template>
  
  <script>
  export default {
    name: 'Hero',
    props: {
        imageSource: String
    }
  }
  </script>
  