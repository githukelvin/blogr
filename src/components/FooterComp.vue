<template>
 <footer>
  <div class="container">
    <div class="content footer">
      <a href="/" class="footerlogo"><img src="/images/logo.svg" alt=""></a>
      <div class="product subfooter">
        <h1>product</h1>
        <ul>
          <li><a href="">overview</a></li>
          <li><a href="">pricing</a></li>
          <li><a href="">marketplace</a></li>
          <li><a href="">features</a></li>
          <li><a href="">integrations</a></li>
        </ul>
      </div>
      <div class="company subfooter">
        <h1>company</h1>
        <ul>
          <li><a href="">about</a></li>
          <li><a href="">team</a></li>
          <li><a href="">blog</a></li>
            <li><a href="">careers</a></li>
        </ul>
      </div>
      <div class="connect subfooter">
        <h1>connect</h1>
        <ul>
          <li><a href="">contact</a></li>
          <li><a href="">newsletter</a></li>
          <li><a href="">linkedIn</a></li>
        </ul>
      </div>
    </div>
  </div>
 </footer>
</template>

<script setup>

</script>

<style lang="scss" scoped>
footer{
  border-top-right-radius:100px ;
  padding-block: 4.3em;
  .footer{
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap:1.9em;
    .subfooter{
      padding-top: .6em;
      ul{
        li{
          padding-bottom:.8em ;
        }
      }
    }
  }
}
</style>
