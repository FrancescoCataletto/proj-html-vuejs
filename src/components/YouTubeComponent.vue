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
                    <h3><i class="fa-solid fa-circle-chevron-down"></i><i class="fa-solid fa-circle-chevron-up"></i>How can we help?</h3>
                    <div class="pop-up">
                        <p>How many courses you've been on, using however many techniques and methods. Unless you've come to realize the value of mindset, then you've yet to understand how success comes.</p>
                        <p>With everyone else's mindset involved impacting too. Hence why business coaching is so crucial for success.</p> 
                    </div>
                  </li>
                  <li>
                    <h3><i class="fa-solid fa-circle-chevron-down"></i><i class="fa-solid fa-circle-chevron-up"></i>How can we help?</h3>
                    <div class="pop-up">
                        <p>How many courses you've been on, using however many techniques and methods. Unless you've come to realize the value of mindset, then you've yet to understand how success comes.</p>
                        <p>With everyone else's mindset involved impacting too. Hence why business coaching is so crucial for success.</p> 
                    </div>
                  </li>
                  <li>
                    <h3><i class="fa-solid fa-circle-chevron-down"></i><i class="fa-solid fa-circle-chevron-up"></i>How can we help?</h3>
                    <div class="pop-up">
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
    background-size: 180px 180px, 700px 400px;
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
        cursor: pointer;
    }
}

#right-wrapped{
    width: 40%;
    margin: 0 auto;
    color: white;
    ul{
        margin-left: -30px;
    }
    h2{
        font-weight: bold;
        margin-bottom: 30px;
    }
    li{
        cursor: pointer;
        list-style: none;
        border-bottom: 1px solid grey;
    }
    i{
        font-size: 20px;
        margin-right: 3px;
    }
    .fa-circle-chevron-up{
            display: none;
    }
    li:hover .fa-circle-chevron-down{
        display: none;
    }
    li:hover .fa-circle-chevron-up{
        display: inline-block;
    }
    .pop-up{
        display: none;
    }
    li:hover h3{
        color: $brand-color;
    }
    li:hover .pop-up{
        display: inline-block;
    }
}
</style>