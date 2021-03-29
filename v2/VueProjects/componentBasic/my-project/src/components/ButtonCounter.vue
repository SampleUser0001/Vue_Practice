<template>
  <button v-on:click="count++">You clicked me {{ count }} times.</button>
</template>

<script>
  export default {
    name: 'button-counter',
    // dataは関数でなければならない。
    data: function () {
      return {
        count: 0
      }
    }
  }
</script>