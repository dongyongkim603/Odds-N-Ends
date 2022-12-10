<template>
    <button
      class="button"
      :type="type"
      @click="onClick"
    >
      <span class="btn__text">{{buttonName}}</span>
    </button>
</template>
  
  <script>
  export default {
    name: 'Button',
    props: {
        diabled: Boolean,
        buttonName: String,
        value: String,
        type: {
          type: String,
          default: "button"
        },
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
    color: rgb(0, 0, 0);
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    background-color: rgb(132, 206, 225);
    border-radius: .5rem;
  }

  .btn__text{ 
    text-decoration: solid;
    font-weight: 600;
    font-family: 'Oswald', sans-serif;

  }
</style>