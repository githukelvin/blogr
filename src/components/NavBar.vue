<template>
   <div class="content navBar">
          <div class="left">
            <a href="/"><img src="/images/logo.svg" alt="" /></a>
            <nav>
              <ul>
                <li>
                  <a href="/product">product</a>
                  <div></div>
                </li>
                <li>
                  <a href="/company">company</a>
                  <div></div>
                </li>
                <li>
                  <a href="/connect">connect</a>
                  <div></div>
                </li>
              </ul>
            </nav>
          </div>
          <div class="right btns">
            <a href="#">login</a>
            <AppButton link="#" text="Sign up" />
          </div>
        </div>
</template>

<script setup>
import AppButton from './AppButton.vue'

</script>

<style lang="scss" scoped>

</style>
