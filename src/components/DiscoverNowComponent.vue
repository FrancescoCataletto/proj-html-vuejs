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
          <div id="middle-discover" class="d-flex">
              <div class="discover-description">
                  <div>
                      <img src="../assets/img/home-business-service-slide-01-480x298.jpg" alt="">
                  </div>
                  <div>
                      <h3>Consultative Training</h3>
                      <p>With a coach addressing multiple issues that are off balance, affecting your business in various unconsidered ways.</p>
                  </div>
                  <div>
                      <a href="#">Discover now</a>
                  </div>
              </div>
              <div class="discover-description">
                  <div>
                      <img src="../assets/img/home-business-service-slide-02-480x298.jpg" alt="">
                  </div>
                  <div>
                      <h3>Consultative Training</h3>
                      <p>With a coach addressing multiple issues that are off balance, affecting your business in various unconsidered ways.</p>
                  </div>
                  <div>
                      <a href="#">Discover now</a>
                  </div>
              </div>
              <div class="discover-description">
                  <div>
                      <img src="../assets/img/home-business-service-slide-03-480x298.jpg" alt="">
                  </div>
                  <div>
                      <h3>Consultative Training</h3>
                      <p>With a coach addressing multiple issues that are off balance, affecting your business in various unconsidered ways.</p>
                  </div>
                  <div>
                      <a href="#">Discover now</a>
                  </div>
              </div>
          </div>
          <div id="bottom-discover">
              ...
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
}

.discover-description{
    text-align: center;
    width: calc(100% / 3);
    img{
        width: 90%;
    }
}

#bottom-discover{
    text-align: center;
}
</style>