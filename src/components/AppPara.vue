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
.para{
  padding-left: 1.9em;
  h1{
    font-size: 1.5em;
  }
  p{
    line-height: 2;
  }
}
</style>
