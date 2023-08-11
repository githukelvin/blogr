<template>
  <main class="content">
    <h2>Designed for the future</h2>
    <section class="sect1">
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
          <img src="/images/illustration-editor-desktop.svg" alt="" />
        </div>
      </div>
    </section>
  </main>
</template>

<script setup>
import AppPara from './AppPara.vue'
</script>

<style lang="scss" scoped>
main {
  h2 {
    text-align: center;
    padding: 4em 0 2.9em;
  }
}
</style>
