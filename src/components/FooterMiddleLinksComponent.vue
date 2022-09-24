<template>
  <div class="bg-dc-big">
    <div class="container links-container">
      <div>
        <h3>DC COMICS</h3>
        <div class="links">
          <a href="#">Characters</a>
          <a href="#">Comics</a>
          <a href="#">Movies</a>
          <a href="#">TV</a>
          <a href="#">Games</a>
          <a href="#">Videos</a>
          <a href="#">News</a>
        </div>
        <h3 class="margin-top-fix">SHOP</h3>
        <div class="links">
          <a href="">Shop DC</a>
          <a href="">Shop DC Collectibles</a>
        </div>
      </div>

      <div>
        <h3>DC</h3>
        <div class="links">
          <a href="#">Terms Of Use</a>
          <a href="#">Privacy policy (New)</a>
          <a href="#">Ad Choises</a>
          <a href="#">Advertising</a>
          <a href="#">Jobs</a>
          <a href="#">Subscriptions</a>
          <a href="#">Talent Workshops</a>
          <a href="#">CPSC Certificates</a>
          <a href="#">Ratings</a>
          <a href="#">Shop Help</a>
          <a href="#">Contact Us</a>
        </div>
      </div>

      <div>
        <h3>SITES</h3>
        <div class="links">
          <a href="">DC</a>
          <a href="">MAD Magazine</a>
          <a href="">DC Kids</a>
          <a href="">DC Universe</a>
          <a href="">DC Power Visa</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.bg-dc-big {
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
}

.links-container {
  display: flex;
  flex-wrap: wrap;
  column-gap: 20px;
  padding-top: 40px;
  padding-bottom: 55px;
  background-image: url("../assets/img/dc-logo-bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-position-x: 100%;

  h3 {
    color: white;
    margin-bottom: 15px;
  }

  .links {
    display: flex;
    flex-direction: column;

    a {
      margin: 4px 0px;
      text-decoration: none;
      color: #696b73;
      font-size: 0.8rem;
    }
  }
}

.margin-top-fix {
  margin-top: 15px;
}

// effects

a:hover {
  transform: scale(1.02);
  filter: brightness(170%);
}
</style>