<template>
  <div class="address-header">
    <span name="font" class="FontFamily i-fanhui" @click="goBack()"></span>
    <slot name="headers"></slot>
  </div>
</template>

<script>
    export default {
       methods: {
         goBack() {
           window.history.back()
         }
       }
    }
</script>

<style scoped>

</style>
