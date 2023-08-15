<script setup>
import DropDown from './DropDown.vue'
import AppButton from './AppButton.vue'
</script>

<template>
  <div class="content navBar">
    <div class="left">
      <a href="/"><img src="/images/logo.svg" alt="" /></a>
      <nav>
        <ul>
          <div class="li1">
            <li>
              <a href="/product">product</a>
              <div id="bg"></div>
            </li>
            <div class="showdropdown">
              <DropDown
                link1="Overview"
                link2="Pricing"
                link3="Marketplace"
                link4="Features"
                link5="Integrations"
              />
            </div>
          </div>
          <div class="li2">
            <li>
              <a href="/company">company</a>
              <div id="bg"></div>
            </li>
            <div class="showdropdown">
              <DropDown
                link1="About"
                link2="Team"
                link3="Blog"
                link4="Careers"
              />
            </div>
          </div>
          <div class="li3">
            <li>
              <a href="/connect">connect</a>
              <div id="bg"></div>
            </li>
            <div class="showdropdown">
              <DropDown
              link1="Contact"
              link2="Newsletter"
               link3="LinkedIn" />
            </div>
          </div>
        </ul>
      </nav>
    </div>
    <div class="right btns">
      <a href="#">login</a>
      <AppButton link="#" text="Sign up" />
    </div>
    <div class="ham"></div>
  </div>
</template>

<style lang="scss" scoped></style>
