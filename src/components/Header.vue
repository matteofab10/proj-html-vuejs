<template>
  <header>
    <div class="mf-head-left container">
      <img src="../assets/img/logo-restaurant-2x-300x58.png" alt="logo-image">
      <div class="mf-card">
        <h6>the best table in town</h6>
        <h1>fine dining experience</h1>
        <h5>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Provident unde nam ab commodi velit sequi. Sit harum sed in, soluta.</h5>
        <button>Explore The Menu</button>
      </div>
    </div>
    <div class="mf-head-right">
      <div class="mf-header-background">
        <nav>
          <ul>
            <li v-for="(link, index) in NavData" :key="index">
              <a :href="link.link">
                {{link.title}}
              </a>
            </li>
            <li><a href=""><i class="fas fa-shopping-cart"></i></a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
import NavData from '../assets/data/NavData.js';


export default {
  name: 'Header',
  data(){
    return {
      NavData,
    }
  }
}
</script>

<style lang="scss">

header {
  display: flex;
  width: 100%;
  min-width: 700px;
  height: 700px;
  background-color: red;
  
  .mf-head-left {
    width: 40%;
    background-color: black;
    img {
      margin: 20px 0 100px 100px;
    }
    .mf-card {
      margin-left: 22%;
      h6 {
        text-transform: uppercase;
        color: #bcbcbc;
        margin-bottom: 25px;
      }
      h1 {
        text-transform: uppercase;
        color: white;
        font-size: 60px;
        font-weight: bold;
        margin-bottom: 25px;
      }
      h5 {
        color: #bcbcbc;
        padding-right: 20%;
        margin-bottom: 40px;
        line-height: 25px;
      }
      button {
        background-color: black;
        color: #bcbcbc;
        text-transform: uppercase;
        font-size: 10px;
        padding: 10px 20px 10px 20px;
        border-color: #bcbcbc;
      }
    }
  }

  .mf-head-right {
    width: 60%;
    .mf-header-background {
      background-image: url('../assets/img/slider52x.jpg');
      width: 100%;
      height: 100%;
      background-size: cover;
      background-repeat: no-repeat;
      background-position: 50% 50%;
    }
    ul {
      display: flex;
      padding-top: 50px;
      justify-content: center;
      li {
        list-style: none;
        margin: 0 30px;
        a {
          text-decoration: none;
          color: #bcbcbc;
        }
      }
      a:hover {
        color: white;
      }
      // a:active {
      //   color: white;
      // }
    }
  }
}

</style>