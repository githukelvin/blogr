<script setup>
import { defineProps } from 'vue'

defineProps({
  text: String,
  title: String
})
</script>

<template>
<div class="para">
  <h1>{{ title }}</h1>
  <p>{{ text }}</p>
</div>
</template>

<style lang="scss" scoped>

</style>
