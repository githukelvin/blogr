<template>
  <main class="container">
   <div class="all">
     <h2>Designed for the future</h2>
      <section class="sect1 topcontent">
        <div class="info">
          <div class="info__left">
            <AppPara
              text="Blogr features an exceedingly intuitive interface which lets you focus on one thing: creating content.
                  The editor supports management of multiple blogs and allows easy manipulation of embeds such as images,
                  videos, and Markdown. Extensibility with plugins and themes provide easy ways to add functionality or
                  change the looks of a blog."
              title="Introducing an extensible editor"
            />
            <AppPara
              text="Flexible content management enables users to easily move through posts. Increase the usability of your blog
                  by adding customized categories, sections, format, or flow. With this functionality, you’re in full control.
                "
              title=" Robust content management"
            />
          </div>
          <div class="info__right">
          </div>
        </div>
      </section>
      <section class="sect2">
        <div class="content details">
          <div class="dleft">
            <img src="/images/illustration-phones.svg" alt="phones illusrations">
          </div>
          <div class="dright">
            <h1> State of the Art Infrastructure</h1>
            <p> With reliability and speed in mind, worldwide data centers provide the backbone for ultra-fast connectivity.
    This ensures your site will load instantly, no matter where your readers are, keeping your site competitive.</p>
          </div>
        </div>
      </section>
   </div>
  </main>
</template>

<script setup>
import AppPara from './AppPara.vue'
</script>

<style lang="scss" scoped>
.all{
  h2 {
    text-align: center;
    padding: 4em 0 2.9em;
  }
  .sect1{
  .info{
    display: grid;
    grid-template-columns: 1fr 1fr;
    &__left{
      display: flex;
      flex-direction: column;
      gap:5em;
      margin-bottom: 16em;
    }
    &__right{
    }
  }
}
.sect2{
  border-bottom-left-radius: 100px;
  height: 400px;
  border-top-right-radius: 100px;
  background-position-y: -500px;
  background-position-x: -210px;
  .details{
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3.9em;
  }
  .dleft{
    margin-top:-4.3em;
    margin-left:-2.5em;
  }
  .dright{
    width: 100%;
    display: flex;
    flex-direction: column;
    margin-top: 7.3em;
    h1{
      margin-left: -1.23em;
      text-align: start;
      font-size: 2.3em;
      margin-bottom: 0;
      padding-bottom: 0;
    }
    p{
    line-height: 1.74;
    width: 100%;
    word-spacing: 2px;
    letter-spacing: .2px;
      margin-left: -1.85em;

  }
  }
}
}

</style>
