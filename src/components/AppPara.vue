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
  padding-left: 1.65em;
  margin-top:-5px;
  h1{
    font-size: 1.72em;
    padding-bottom: .88em;
  }
  p{
    line-height: 1.74;
    width: 86%;
    word-spacing:2px;
    letter-spacing: .2px;
  }
}
</style>
