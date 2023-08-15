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
      <section class="sect3 lastcontent">
        <div class="infolast">
          <div class="infolast__right"></div>
          <div class="infolast__left">
            <AppPara
            title="Free, open, simple"
            text="Blogr is a free and open source application backed by a large community of helpful developers. It supports
  features such as code syntax highlighting, RSS feeds, social media integration, third-party commenting tools,
  and works seamlessly with Google Analytics. The architecture is clean and is relatively easy to learn."
            />
            <AppPara
            title="Powerful tooling"
            text="Batteries included. We built a simple and straightforward CLI tool that makes customization and deployment a breeze, but
  capable of producing even the most complicated sites."
            />
          </div>
        </div>
      </section>
   </div>
  </main>
  <FooterComp/>
</template>

<script setup>
import FooterComp from './FooterComp.vue'
import AppPara from './AppPara.vue'
</script>

<style lang="scss" scoped>
.all{
  h2 {
    text-align: center;
    padding: 4em 0 2.9em;
  }

}

</style>
