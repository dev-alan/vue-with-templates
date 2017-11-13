<template>
  <div id="main-menu">
    <button class="button button-close">{{ message }}</button>
  </div>
</template>

<script>
  export default {
    name: 'menuMain',
    data() {
      return {
        message: 'main menu'
      }
    }
  }
</script>

<style scoped>
  .button {
    border: none;
    border-radius: 2px;
  }
  .button-close {
    background-color: red;
  }
</style>