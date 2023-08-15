<template>
  <a class="btn"  :href="link">{{text}}</a>
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
  text: String,
  link: String
})
</script>

<style lang="scss" scoped>
.btn{
  padding: .9em 2.5em;
  margin-right: -8px;
  background: #fff;
  border-radius: 35px;

}
</style>
