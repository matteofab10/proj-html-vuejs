<template>
  <footer>
    <div class="mf-footer-top">
      FOOTER TOP
    </div>
    <div class="mf-footer-bottom">
      FOOTER BOTTOM
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss">

footer {
  width: 100%;
  height: 450px;
  background-color: steelblue;
  .mf-footer-top {
    height: 380px;
    background-image: url('../assets/img/footer2x.jpg');
    width: 100%;
    background-size: contain;
    
  }
  .mf-footer-bottom {
    height: 70px;
    background-color: black;
  }
}

</style>