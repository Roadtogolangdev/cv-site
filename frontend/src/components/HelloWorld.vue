<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="greetings-text">{{ msg }}</h1>
  </div>
</template>

<style scoped>

</style>
