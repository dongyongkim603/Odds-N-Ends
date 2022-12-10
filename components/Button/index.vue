<template>
    <button
    class="button"
    @click="onClick"
    >
      {{buttonName}}
    </button>
</template>
  
  <script>
  export default {
    name: 'Button',
    props: {
        diabled: Boolean,
        buttonName: String,
        value: String,
        type: String,
        onClick: {
          type: Function,
          default: () => null
        }
    },
    methods: {
      clickFunction() {
        debugger
        console.log('I been clicked bruh');
      }
    }
  }
  </script>
  
<style lang="scss" scoped>
.button {
  border: none;
  color: rgb(165, 59, 59);
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
</style>