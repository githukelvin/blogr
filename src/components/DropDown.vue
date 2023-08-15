<template>
  <div class="dropdown">
    <ul>
      <li>
        <a href="">{{ link1 }}</a>
      </li>
      <li>
        <a href="">{{ link2 }}</a>
      </li>
      <li>
        <a href="">{{ link3 }}</a>
      </li>
      <li>
        <a href="">{{ link4 }}</a>
      </li>
      <li>
        <a href="">{{ link5 }}</a>
      </li>
    </ul>
  </div>
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
  link1: String,
  link2: String,
  link3: String,
  link4: String,
  link5: String
})
</script>

<style lang="scss" scoped>
.dropdown{
  background: #fff;
  border-radius: 5px;
  padding: 1.5em 2em;
  margin-top: 1em;
  width: 220px;
 ul{
   display: flex;
  flex-direction: column;
 }
}
</style>
