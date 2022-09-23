<template>
    <div class="top-footer">
        <div class="container">
            <div class="card">
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                
                <span>DIGITAL COMICS</span>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                
                <span>DC MERCHANDISE</span>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                
                <span>SUBSCRIPTION</span>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                
                <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
  </template>
  
  <script>

  export default {
  
  }
  </script>
  
  <style lang="scss" scoped>
    @import '../styles/variables.scss';
  
.top-footer {
   background-color: $bg-blue;
}

.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 55px 0px;

    div {
        display: flex;
        align-items: center;

        img {
            height: 55px;
        }

        span {
            margin-left: 15px;
            color: white;
        }

        &.card {
            height: 55px;
        }
    }
}

.container .card:nth-child(5) div img {
    height: 35px;
}

  </style>