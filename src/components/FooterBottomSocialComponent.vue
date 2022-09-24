<template>
  <div>
    <div class="bg-footer-bottom">
      <div class="container">
        <div>
          <button><h4>SIGN-UP NOW!</h4></button>
        </div>

        <div class="bottom-footer-social-icons">
          <h3>FOLLOW US</h3>
          <div>
            <img src="../assets/img/footer-facebook.png" alt="" />
          </div>
          <div>
            <img src="../assets/img/footer-twitter.png" alt="" />
          </div>
          <div>
            <img src="../assets/img/footer-youtube.png" alt="" />
          </div>
          <div>
            <img src="../assets/img/footer-pinterest.png" alt="" />
          </div>
          <div>
            <img src="../assets/img/footer-periscope.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
  
  <script>
export default {};
</script>
  
  <style lang="scss" scoped>
@import "../styles/variables.scss";

.bg-footer-bottom {
  background-color: $footer-color;
}

.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  padding: 35px 0px;

  button {
    color: white;
    background-color: inherit;
    border: 2px solid #0282f9;
    padding: 15px;
    cursor: pointer;

    h4 {
      font-size: 1rem;
    }
  }
}

.bottom-footer-social-icons {
  display: flex;
  align-items: center;
  column-gap: 20px;

  h3 {
    color: #0581f9;
    font-size: 1.4rem;
  }

  img {
    cursor: pointer;
  }
}

// effects

button:hover {
  filter: brightness(120%);
}

button:active {
  transform: scale(0.95);
}

.bottom-footer-social-icons img:hover {
  cursor: pointer;
  transform: scale(1.1);
  filter: brightness(120%);
}

.bottom-footer-social-icons img:active {
  transform: scale(0.95);
}
</style>