<template>
  <header>
    <div class="mf-head-left container">
      <img src="../assets/img/logo-restaurant-2x-300x58.png" alt="logo-image">
      <div class="mf-card">
        <h6>the best table in town</h6>
        <h1>fine dining experience</h1>
        <h5>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Provident unde nam ab commodi velit sequi. Sit harum sed in, soluta adipisci iusto dolores vitae nostrum incidunt neque dolor dolore nam.</h5>
        <button>Explore The Menu</button>
      </div>
    </div>
    <div class="mf-head-right">
      <div class="mf-header-background">
        <nav>
          <ul>
            <li><a href="">Home</a></li>
            <li><a href="">Culinary History</a></li>
            <li><a href="">Our Team</a></li>
            <li><a href="">Our Menu</a></li>
            <li><a href="">Takeout</a></li>
            <li><a href="">Bulletin</a></li>
            <li><a href="">Reservation</a></li>
            <li><a href="">Carrello</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss">

header {
  display: flex;
  width: 100%;
  height: 700px;
  background-color: red;
  
  .mf-head-left {
    width: 40%;
    background-color: black;
  }

  .mf-head-right {
    width: 60%;
    .mf-header-background {
      background-image: url('../assets/img/slider52x.jpg');
      width: 100%;
      height: 700px;
      background-size: cover;
    }
    ul {
      display: flex;
      padding-top: 50px;
      justify-content: center;
      li {
        list-style: none;
        margin: 0 auto;
        font-weight: 700;
        a {
          text-decoration: none;
          color: grey;
        }
      }
      a:hover {
        color: white;
      }
    }
  }
}

</style>