<template lang="pug">
  button {{ title }}
</template>

<script>
export default {
  name: 'BaseHeader',
  props: {
    title: {
      type: String,
      default: '',
    },
  },
}
</script>

<style lang="scss" scoped>
button {
  .bt {
    counter-reset: 1;
  }
  background: blue;
}
</style>
