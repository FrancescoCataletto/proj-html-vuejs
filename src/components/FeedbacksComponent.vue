<template>
  <div id="feedbacks">
      <div id="top-feedbacks">
          <h3>People are praising Maxcoach</h3>
          <h2>What make they love us?</h2>
      </div>
      <div id="middle-feedbacks" class="d-flex">
          <div class="feedbacks-card">
              <h6>It's a choice of quality for people with special needs</h6>
              <p>I'm a very strict person so I required everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
              <div class="d-flex">
                  <img src="../assets/img/testimonial-avata-03.jpg" alt="">
                  <div>
                      <h6>FLORENCE THIMES</h6>
                      <P>/ Multimedia Admin</P>
                  </div>
              </div>
          </div>
          <div class="feedbacks-card">
              <h6>It's a choice of quality for people with special needs</h6>
              <p>I'm a very strict person so I required everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
              <div class="d-flex">
                  <img src="../assets/img/testimonial-avata-03.jpg" alt="">
                  <div>
                      <h6>FLORENCE THIMES</h6>
                      <P>/ Multimedia Admin</P>
                  </div>
              </div>
          </div>
          <div class="feedbacks-card">
              <h6>It's a choice of quality for people with special needs</h6>
              <p>I'm a very strict person so I required everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
              <div class="d-flex">
                  <img src="../assets/img/testimonial-avata-03.jpg" alt="">
                  <div>
                      <h6>FLORENCE THIMES</h6>
                      <P>/ Multimedia Admin</P>
                  </div>
              </div>
          </div>
      </div>
      <div id="bottom-feedbacks">
          ....
      </div>
  </div>
</template>

<script>
export default {
    name: "FeedbacksComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

#feedbacks{
    background-color: rgb(248, 248, 248);
    margin: 30px 0;
}

#top-feedbacks{
    text-align: center;
}

#middle-feedbacks{
    width: 95%;
    margin: 0 auto;
    img{
        height: 80px;
        width: 80px;
        border-radius: 50%;
        margin-right: 20px;
    }
}

.feedbacks-card{
    background-color: rgb(255, 255, 255);
    width: calc(100% / 3 - 60px);
    margin: 0 30px;
    padding: 40px;
}

#bottom-feedbacks{
    text-align: center;
}
</style>