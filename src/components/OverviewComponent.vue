<template>
  <div id="overview">
      <div id="wrapper">
          <div id="top-wrapper">
              <h3>
                  Let's Dream Big Together
              </h3>
              <h2>
                  We are pioneers of the digital approach, using leading-edge technology to simplify procedures and apply executive coaching in the new age of digitalization.
              </h2>
          </div>
          <div id="middle-wrapper" class="d-flex flex-wrap">
              <div class="overview-card d-flex">
                  <div><i class="fa-light fa-gear"></i></div>
                  <div>
                      <h3>One to One</h3>
                      <p>Getting the necessary clarity about the current state to help you improve your game.</p>
                  </div>
              </div>
              <div class="overview-card d-flex">
                  <div><i class="fa-light fa-gear"></i></div>
                  <div>
                      <h3>Anywhere</h3>
                      <p>Access to valuable and portable program which allow you to setup and live anywhere you want.</p>
                  </div>
              </div>
              <div class="overview-card d-flex">
                  <div><i class="fa-light fa-gear"></i></div>
                  <div>
                      <h3>On Time</h3>
                      <p>Punctuality is our top priority because it's an essential criteria to assess a program quality.</p>
                  </div>
              </div>
              <div class="overview-card d-flex">
                  <div><i class="fa-light fa-gear"></i></div>
                  <div>
                      <h3>Online Courses</h3>
                      <p>Online business coaching now offers you a very powerful way to empower your business into success.</p>
                  </div>
              </div>
              <div class="overview-card d-flex">
                  <div><i class="fa-light fa-gear"></i></div>
                  <div>
                      <h3>Consulting</h3>
                      <p>You will get a clear sense of direction for your business, thorough assessment and faster results.</p>
                  </div>
              </div>
              <div class="overview-card d-flex">
                  <div><i class="fa-light fa-gear"></i></div>
                  <div>
                      <h3>Self Development</h3>
                      <p>Business Coaching often keep your focus and develop you both in a professional and personal way.</p>
                  </div>
              </div>
          </div>
          <div id="bottom-wrapper">
              <button id="learn">Learn More</button>
              <button id="start">Get started today</button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "OverviewComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

#wrapper{
    width: 70%;
    margin: 0 auto;
    padding: 30px 0;
}

#top-wrapper{
    text-align: center;
    width: 80%;
    margin: 0 auto;
    h3{
        color: $brand-color;
        font-size: 18px;
        margin: 30px;
    }
    h2{
        font-weight: bold;
        color: rgb(51, 51, 51);
    }
}

#middle-wrapper{
    margin: 50px 0;
}

.overview-card{
    width: calc(100% / 3);
    padding: 20px;
    div:first-child{
        width: 20%;
    }
}

#bottom-wrapper{
    text-align: center;
    margin-bottom: 40px;
}

#learn{
    background-color: white;
    color: $brand-color;
    border-radius: 5px;
    padding: 15px 50px;
    margin-right: 20px;
    border: 2px solid rgb(238, 238, 238);
}

#start{
    color: white;
    background-color: $brand-color;
    border-radius: 5px;
    padding: 15px 30px;
    border: 2px solid $brand-color;
}
</style>