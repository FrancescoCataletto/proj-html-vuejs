<template>
  <div>
      <div id="discover">
          <div id="top-discover">
              <h3>
                  Let's Dream Big Together
              </h3>
              <h2>
                  Explore How can I help you
              </h2>
          </div>
          <div id="middle-discover" class="d-flex flex-wrap">
              <div class="discover-description">
                  <div>
                      <img src="../assets/img/home-business-service-slide-01-480x298.jpg" alt="">
                  </div>
                  <div class="card-text">
                      <h3>Consultative Training</h3>
                      <p>With a coach addressing multiple issues that are off balance, affecting your business in various unconsidered ways.</p>
                  </div>
                  <div class="card-link">
                      <a href="#">Discover now<i class="fa-solid fa-arrow-right"></i></a>
                  </div>
              </div>
              <div class="discover-description">
                  <div>
                      <img src="../assets/img/home-business-service-slide-02-480x298.jpg" alt="">
                  </div>
                  <div class="card-text">
                      <h3>Real Deal Coaching</h3>
                      <p>Brings an exceptionally powerful opportunity. Being able to accept, to work with that opportunity.</p>
                  </div>
                  <div class="card-link">
                      <a href="#">Discover now<i class="fa-solid fa-arrow-right"></i></a>
                  </div>
              </div>
              <div class="discover-description">
                  <div>
                      <img src="../assets/img/home-business-service-slide-03-480x298.jpg" alt="">
                  </div>
                  <div class="card-text">
                      <h3>Advisor Training Program</h3>
                      <p>Getting high quality, entrepreneur mindset driven online business coaching, is what is needed.</p>
                  </div>
                  <div class="card-link">
                      <a href="#">Discover now<i class="fa-solid fa-arrow-right"></i></a>
                  </div>
              </div>
          </div>
          <div id="bottom-discover">
              <i class="fa-solid fa-ellipsis"></i>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "DiscoverNowComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";
*{
    background-color: rgb(248, 248, 248);
}

#discover{
    width: 70%;
    margin: 0 auto;
    padding: 30px 0;
}

#top-discover{
    text-align: center;
    margin-bottom: 30px;
    h3{
        color: $brand-color;
        font-size: 18px;
        margin-top: 40px;
    }
    h2{
        font-weight: bold;
    }
}

.discover-description{
    text-align: center;
    width: calc(100% / 3 - 40px);
    margin: 0 20px;
    background-color: white;
    box-shadow: 0px 1px 5px 0px;
    h3, p, a{
        background-color: white;
    }
    img{
        width: 100%
    }
}

.card-text{
    padding: 20px;
    background-color: white;
    min-height: 200px;
}

.card-link{
    background-color: white;
    padding: 10px 0;
    border-top: 1px solid rgb(247, 247, 247);
    a{
        text-decoration: none;
        color: $brand-color;
        font-size: 14px;
    }
    i{
        font-size: 10px;
        margin-left: 3px;
    }
}

#bottom-discover{
    text-align: center;
    margin-top: 20px;
    font-size: 30px;
}
</style>