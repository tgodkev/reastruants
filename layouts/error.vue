<template>
  <div>
    <slot name="header"/>
  </div>
  <slot name="redirectEl"></slot>
</template>

<script>
export default {
  name: "error"
}
</script>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>
