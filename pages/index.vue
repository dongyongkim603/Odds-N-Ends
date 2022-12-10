<template>
  <div>
    <Hero :imageSource="imageSrc"/>
    <Button 
      :buttonName="'Click Me!'"
      :onClick="() => clickTest()"
    />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      imageSrc: "",
      counter: 0
    }
  },  
  methods: {
    clickTest() {
      if(this.counter % 2 === 0) {
        this.imageSrc = "https://www.idlememe.com/wp-content/uploads/2022/09/shrek-meme-idlememe-18-300x472.jpg"
      } else {
        this.imageSrc = "https://cdn.custom-cursor.com/packs/476/pack437.png"
      }
      this.counter++;
    }
  }
}
</script>
