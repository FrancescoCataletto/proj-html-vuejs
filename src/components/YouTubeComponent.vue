<template>
  <div id="you-tube" class="d-flex align-items-center">
      <div id="wrapper" class="d-flex align-items-center">
          <div id="left-wrapped">
              <img src="../assets/img/home-business-video-poster-670x450.jpg" alt="">
              <div>
                  <img src="../assets/img/icon-youtube-play.png" alt="">
              </div>
          </div>
          <div id="right-wrapped">
              <h2>
                  To Thrive In Business Today, You'll Need a Good Plan
              </h2>
              <ul>
                  <li>
                    <h3>How can we help?</h3>
                    <div>
                        <p>How many courses you've been on, using however many techniques and methods. Unless you've come to realize the value of mindset, then you've yet to understand how success comes.</p>
                        <p>With everyone else's mindset involved impacting too. Hence why business coaching is so crucial for success.</p> 
                    </div>
                  </li>
                  <li>
                    <h3>How can we help?</h3>
                    <div>
                        <p>How many courses you've been on, using however many techniques and methods. Unless you've come to realize the value of mindset, then you've yet to understand how success comes.</p>
                        <p>With everyone else's mindset involved impacting too. Hence why business coaching is so crucial for success.</p> 
                    </div>
                  </li>
                  <li>
                    <h3>How can we help?</h3>
                    <div>
                        <p>How many courses you've been on, using however many techniques and methods. Unless you've come to realize the value of mindset, then you've yet to understand how success comes.</p>
                        <p>With everyone else's mindset involved impacting too. Hence why business coaching is so crucial for success.</p> 
                    </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "YouTubeComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

#you-tube{
    background: url("../assets/img/maxcoach-shape-07.png") left 100px bottom no-repeat, url("../assets/img/background-map-dots-top-right-transparent.png") right top no-repeat;
    background-color: rgb(50, 48, 67);
    background-size: 100px 100px, 700px 400px;
    height: 600px;
}

#wrapper{
    width: 70%;
    margin: 30px auto;
}

#left-wrapped{
    width: 40%;
    position: relative;
    img:first-child{
        width: 100%
    }
    div{
        position: absolute;
        top: 40%;
        left: 40%;
    }
}

#right-wrapped{
    width: 50%;
    margin: 0 auto;
}
</style>