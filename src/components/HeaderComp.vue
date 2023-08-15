<template>
  <header>
    <div class="container">
     <NavBar/>
    </div>
    <div class="middleContent">
      <h1>A modern publishing platform</h1>
      <p>Grow your audience and build your online brand</p>
      <div class="btns">
        <AppButton id="hey" link="#" text="Start for Free" />
        <a class='learn' href="#">Learn More</a>
      </div>
    </div>
  </header>
</template>

<script setup>
import NavBar from './NavBar.vue'
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
      &:hover{
      }
    }
    .learn{
    &:hover{
        color:hsl(356, 100%, 66%);
    }
}
  }
}
</style>
