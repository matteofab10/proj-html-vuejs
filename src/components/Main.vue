<template>
  <main>
    <section class="mf-food">

      <div class="mf-food-top container ps-0 pe-0">
        <div class="mf-food-top-left">
          <h5>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Modi atque soluta consectetur nobis amet similique omnis dolorum aliquam error tempore, id expedita quas repellendus consequatur assumenda obcaecati! Sunt, possimus ea!</h5>
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
          <h2>1</h2>
          <h2>2</h2>
          <h3>3</h3>
        </div>
      </div>

    </section>
    <section class="section-2">
      SECTION 2
    </section>
    <section class="section-3">
      SECTION 3
    </section>
    <section class="section-4">
      SECTION 4
    </section>
    <section class="section-5">
      SECTION 5
    </section>
    <section class="section-6">
      SECTION 6
    </section>
    <section class="section-7">
      SECTION 7
    </section>
    <section class="section-8">
      SECTION 8
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
  height: 900px;
  background-color: saddlebrown;
  .mf-food-top {
    display: flex;
    height: 600px;
    width: 100%;
    background-color: white;
    .mf-food-top-left {
      width: 50%;
      background-color: teal;
      img {
        width: 30%;
      }
    }
    .mf-food-top-right {
      width: 50%;
      background-color: yellowgreen;
      background-image: url('../assets/img/info22x.jpg');
      background-size: cover;
    }
  }
  .mf-food-bottom {
    height: 300px;
    width: 100%;
    background-color: tan;
    .mf-food-bottom-box {
      display: flex;
      justify-content: space-between;
    }
  }
}

.section-2 {
  width: 100%;
  height: 600px;
  background-color: blue;
}

.section-3 {
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