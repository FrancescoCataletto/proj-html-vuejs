<template>
  <div id="feedbacks">
      <div id="shadow"></div>
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
          <div class="feedbacks-card card-focus">
              <h6>It's a choice of quality for people with special needs</h6>
              <p>I'm a very strict person so I required everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
              <div class="d-flex">
                  <img src="../assets/img/testimonial-avata-02.jpg" alt="">
                  <div>
                      <h6>MINA HOLLACE</h6>
                      <P>/ Freelancer</P>
                  </div>
              </div>
          </div>
          <div class="feedbacks-card">
              <h6>It's a choice of quality for people with special needs</h6>
              <p>I'm a very strict person so I required everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
              <div class="d-flex">
                  <img src="../assets/img/testimonial-avata-04.jpg" alt="">
                  <div>
                      <h6>MADLEY PONDOR</h6>
                      <P>/ IT Specialist</P>
                  </div>
              </div>
          </div>
      </div>
      <div id="bottom-feedbacks" class="d-flex justify-content-center">
        <div id="selected"></div>
        <div></div>
        <div></div>
        <div></div>
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
    position: relative;
}

#feedbacks::before{
    content: "";
    position: absolute;
    background-color: white;
    top: -300px;
    right: 0px;
    height: 300px;
    width: 700px;
    border-bottom-right-radius: 100%;
    z-index: 1;
}

#shadow{
    position: absolute;
    height: 300px;
    width: 700px;
    background-color: rgb(248, 248, 248);
    top: -300px;
    right: 0px;
    z-index: 0;
}

#top-feedbacks{
    text-align: center;
    padding: 40px 0;
    h3{
        color: $brand-color;
        font-size: 18px;
    }
    h2{
        font-weight: bold;
    }
}

#middle-feedbacks{
    width: 95%;
    margin: 0 auto;
    img{
        height: 60px;
        width: 60px;
        border-radius: 50%;
        margin-right: 20px;
    }
}

.feedbacks-card{
    background-color: rgb(255, 255, 255);
    width: calc(100% / 3 - 60px);
    margin: 0 30px;
    padding: 40px;
    opacity: 0.5;
    h6{
        color: rgb(65, 60, 102);
        font-weight: bold;
    }
    cursor: pointer;
    .d-flex{
        margin-top: 30px;
        div{
            h6{
               color: rgb(65, 60, 102);
               font-size: 14px;
               font-weight: bold;
            }
            p{
                margin-top: 10px;
                font-size: 12px;
                color: grey;
            }
        }
    }
}

.card-focus{
    opacity: 1;
}

#bottom-feedbacks{
    text-align: center;
    padding: 40px 0;
    div{
        background-color: black;
        opacity: 0.2;
        padding: 5px;
        border-radius: 50%;
        margin: 0 10px;
        cursor: pointer;
    }
    #selected{
            background-color: black;
            opacity: 1;
            padding: 5px;
            border-radius: 50%;
            margin: 0 10px;
    }
}
</style>