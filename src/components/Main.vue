<template>
  <main>
    <section class="mf-food">

      <div class="mf-food-top container ps-0 pe-0">
        <div class="mf-food-top-left">
          <h5><span>Lorem ipsum dolor, sit amet</span> consectetur adipisicing elit. Modi atque soluta consectetur nobis amet similique omnis dolorum aliquam error tempore, id expedita quas repellendus consequatur assumenda obcaecati! Sunt, possimus ea!</h5>
          <h2>Food is our common ground, a universal experience.</h2>
          <h5>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam illo molestiae laudantium eius quae suscipit tempora. Excepturi doloremque tempora quia. Nisi, vero amet? Aut impedit, doloribus beatae atque distinctio quis?</h5>
          <img src="../assets/img/signature.jpg" alt="signature-image">
        </div>
        <div class="mf-food-top-right">
          <h6>california rolls - $22</h6>
        </div>
      </div>

      <div class="mf-food-bottom">
        <div class="mf-food-bottom-box container">
          <div class="mf-food-bottom-card">
            <img src="../assets/img/sushi-1.png" alt="sushi-1-png">
            <h4>the best table in town</h4>
            <h5>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat sit perferendis porro dicta officiis minima voluptate iure, Quaerat sit perferendis porro dicta officiis minima voluptate iure</h5>
            <button>explore the menu</button>
          </div>
          <div class="mf-food-bottom-card">
            <img src="../assets/img/sushi-2.png" alt="sushi-2-png">
            <h4>perfect for groups</h4>
            <h5>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat sit perferendis porro dicta officiis minima voluptate iure, Quaerat sit perferendis porro dicta officiis minima voluptate iure</h5>
            <button>make a reservation</button>
          </div>
          <div class="mf-food-bottom-card">
            <img src="../assets/img/sushi-3.png" alt="sushi-3-png">
            <h4>fresh produce everyday</h4>
            <h5>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat sit perferendis porro dicta officiis minima voluptate iure, Quaerat sit perferendis porro dicta officiis minima voluptate iure</h5>
            <button>learn more about us</button>
          </div>
        </div>
      </div>

    </section>
    <section class="mf-table-in-town">
      <div class="mf-table-left">
        <img src="../assets/img/slider32x.jpg" alt="slider32-image">
      </div>
      <div class="mf-table-right">
        <div class="mf-card">
          <h6>fine dining experience</h6>
          <h1>the best table in town</h1>
          <h5>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Provident unde nam ab commodi velit sequi. Sit harum sed in, soluta.</h5>
          <button>explore the menu</button>
        </div>
      </div>
    </section>
    <section class="mf-critics">

    </section>
  </main>
</template>

<script>
export default {
  name: 'Main'
}
</script>

<style lang="scss">

.mf-food {
  width: 100%;
  background-color: white;
  .mf-food-top {
    display: flex;
    width: 100%;
    padding-top: 100px;
    .mf-food-top-left {
      width: 50%;
      background-color: white;
      padding-top: 80px;
      padding-right: 50px;
      h5 {
        font-size: 15px;
        line-height: 25px;
        span {
          text-transform: uppercase;
          font-weight: bold;
        }
      }
      h2 {
        font-weight: bold;
        text-transform: uppercase;
        font-size: 40px;
        padding: 20px 0;
      }
      img {
        padding-top: 20px;
        width: 30%;
      }
    }
    .mf-food-top-right {
      width: 50%;
      background-color: yellowgreen;
      background-image: url('../assets/img/info22x.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: 50% 50%;
      h6 {
        text-align: center;
        color: #bcbcbc;
        text-transform: uppercase;
      }
    }
  }
  .mf-food-bottom {
    width: 100%;
    padding: 100px 0;
    background-color: white;
    .mf-food-bottom-box {
      display: flex;
      justify-content: space-between;
      .mf-food-bottom-card {
        text-align: center;
        width: 33%;
        h4 {
          text-transform: uppercase;
          font-size: 25px;
          font-weight: bold;
          padding-bottom: 20px;
          padding-top: 30px;
        }
        h5 {
          font-size: 15px;
          padding-bottom: 20px;
          line-height: 25px;
        }
        button {
          background-color: white;
          color: black;
          text-transform: uppercase;
          font-size: 10px;
          padding: 10px 20px 10px 20px;
          border: none;
        }
      }
    }
  }
}

.mf-table-in-town {
  display: flex;
  width: 100%;
  height: 700px;
  .mf-table-left {
    width: 60%;
    img {
      width: 100%;
      height: 700px;
      object-fit: cover;
    }
  }
  .mf-table-right {
    width: 40%;
    background-color: black;
    .mf-card {
      width: 80%;
      margin: 0 auto;
      padding: 150px 0 150px 0;
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
}

.mf-critics {
  width: 100%;
  height: 900px;
  background-color: saddlebrown;
}

.section-4 {
  width: 100%;
  height: 450px;
  background-color: violet;
}

.section-5 {
  width: 100%;
  height: 700px;
  background-color: rosybrown;
}

.section-6 {
  width: 100%;
  height: 600px;
  background-color: salmon;
}

.section-7 {
  width: 100%;
  height: 800px;
  background-color: seagreen;
}

.section-8 {
  width: 100%;
  height: 700px;
  background-color: sandybrown;
}

</style>