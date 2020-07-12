<template src="./preview.html"></template>

<script>
  export default {
    data () {
      return {
        borderRadius: 'default',
      }
    },

    computed: {
      borderRadiusClass () {
        return this.borderRadius === 'default' ? 'rounded' : 'rounded-' + this.borderRadius
      },
    },
  }
</script>

<style src="./tailwind.css"></style>
<style src="./preview.scss" lang="scss"></style>
