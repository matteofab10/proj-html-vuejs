<template>
  <footer>
    <div class="mf-footer-background">
      <div class="mf-footer-top">
        <img src="../assets/img/logo-restaurant-2x-300x58.png" alt="logo-image">
        <p>Quan eu proin sit massa condimentum. Volutpat non pulvinar aliquet nunc. quam eu proin sit massa condimentum.</p>
        <div class="mf-social">
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-youtube"></i>
          <i class="fab fa-instagram"></i>
          <i class="fab fa-linkedin-in"></i>
        </div>
      </div>
    </div>
    <div class="mf-footer-bottom">
      <ul>
        <li v-for="(link, index) in creditsLinks" :key="`credits${index}`">
          <a :href="link.link">{{link.title}} </a> | 
        </li>



        <!-- <li><a href="">All right Reserved  </a> | </li>
        <li><a href="">Powered by <span>WordPress</span> </a> | </li>
        <li><a href="">ThemeFusion</a></li> -->
      </ul>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    creditsLinks: Array,
  }
}
</script>

<style lang="scss">

footer {
  width: 100%;
  height: 450px;
  .mf-footer-background {
    display: flex;
    justify-content: center;
    align-items: center;
    align-content: center;
    text-align: center;
    background-image: url('../assets/img/footer2x.jpg');
    width: 100%;
    height: 380px;
    background-size: cover;
    background-position: 50% 50%;
    .mf-footer-top {
      width: 30%;
      img {
        padding-top: 30px;
      }
      p {
        padding-top: 40px;
        color: #bcbcbc;
      }
      .mf-social {
        display: flex;
        justify-content: center;
        line-height: 30px;
        i {
          display: flex;
          justify-content: center;
          align-items: center;
          width: 30px;
          height: 30px;
          color: black;
          padding: 20px 20px;
          margin: 10px;
          background-color: white;
          border-radius: 50%;
          cursor: pointer;
        }
      }
    }
  }
  .mf-footer-bottom {
    width: 100%;
    background-color: black;
    ul {
      height: 70px;
      display: flex;
      justify-content: center;
      align-content: center;
      align-items: center;
      list-style: none;
    }
    li {
      color: #bcbcbc;
      margin: 0 2px;
      span {
        font-weight: bold;
      }
    }
    a {
      text-decoration: none;
      color: #bcbcbc;
    }
  }
}

</style>