<template>
  <header>
    <div class="container">
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
    </div>
    <div class="middleContent">
      <h1>A modern publishing platform</h1>
      <p>Grow your audience and build your online brand</p>
      <div class="btns">
        <AppButton id="hey" link="#" text="Start for Free" />
        <a href="#">Learn More</a>
      </div>
    </div>
  </header>
</template>

<script setup>
import AppButton from './AppButton.vue'
</script>

<style lang="scss" scoped>
.middleContent {
  width: fit-content;
  margin-inline: auto;
  margin-top: 8em;

  h1,
  p {
    text-align: center;
    color: #fff;
  }
  h1 {
    font-size: 3.65rem;
  }
  p {
    font-size: 1.2rem;
    padding: .8em 0;
    word-spacing: 2px;
  }
  .btns{
    margin-top: 2em;
    gap: 1em;
    display: flex;
    flex-direction: row;
    width: fit-content;
    margin-inline:auto;
    font-size: 1rem;

    #hey{
      padding: .85em;
      margin-right: 0;
    }
  }
}
</style>
