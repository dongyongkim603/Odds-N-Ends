<template>
  <div>
    <Hero :imageSource="'https://www.google.com/url?sa=i&url=http%3A%2F%2Ft0.gstatic.com%2Flicensed-image%3Fq%3Dtbn%3AANd9GcQ76JWs-bsZOrqtpjblvp6TOvYdxRaOTt5pHnN1X3P0y9Q7ERZggupGsG8riY2eP8UOqaw4z7qa0iRc1MU&psig=AOvVaw3wWWfyiDzi32eeaBVl8SNd&ust=1670787558906000&source=images&cd=vfe&ved=0CAgQjRxqFwoTCODT9-jm7_sCFQAAAAAdAAAAABAE'"/>
    <Button 
      :buttonName="'Click Me!'"
      :onClick="() => clickTest()"
    />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  methods: {
    clickTest() {
      debugger
      console.log('toca mi ano')
    }
  }
}
</script>
