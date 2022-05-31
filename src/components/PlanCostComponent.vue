<template>
  <div id="plan-cost">
      <div id="plan-cost-top">
          <h3>Let's Dream Big Together</h3>
          <h2>Explore How Can I help you</h2>
      </div>
      <div id="plan-cost-middle" class="d-flex">
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div class="basic-info">
                  <p>$40.00</p>
                  <p>Learning to Write as  Professional Author</p>
              </div>
              <div class="show-on-hover">
                  <div class="d-flex">
                      <p><i class="fa-solid fa-file-lines"></i>20 Lessons</p>
                      <p><i class="fa-solid fa-user"></i>50 Students</p>
                  </div>
                  <p>The purpose of this course is to provide the advanced writing techniques commonly used for inspiring readers and...</p>
              </div>
          </div>
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div class="basic-info">
                  <p>Free</p>
                  <p>Customer-centric Info-Tech Strategies</p>
              </div>
              <div class="show-on-hover">
                  <div class="d-flex">
                      <p><i class="fa-solid fa-file-lines"></i>20 Lessons</p>
                      <p><i class="fa-solid fa-user"></i>50 Students</p>
                  </div>
                  <p>The purpose of this course is to provide the advanced writing techniques commonly used for inspiring readers and...</p>
              </div>
          </div>
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div class="basic-info">
                  <p>$19.00</p>
                  <p>Open Programming Courses for Everyone: Python</p>
              </div>
              <div class="show-on-hover">
                  <div class="d-flex">
                      <p><i class="fa-solid fa-file-lines"></i>20 Lessons</p>
                      <p><i class="fa-solid fa-user"></i>50 Students</p>
                  </div>
                  <p>The purpose of this course is to provide the advanced writing techniques commonly used for inspiring readers and...</p>
              </div>
          </div>
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div class="basic-info">
                  <p>$26.00</p>
                  <p>Academic Listening and Note-taking</p>
              </div>
              <div class="show-on-hover">
                  <div class="d-flex">
                      <p><i class="fa-solid fa-file-lines"></i>20 Lessons</p>
                      <p><i class="fa-solid fa-user"></i>50 Students</p>
                  </div>
                  <p>The purpose of this course is to provide the advanced writing techniques commonly used for inspiring readers and...</p>
              </div>
          </div>
      </div>
      <div id="plan-cost-bottom">
          <p>Take the control of their life back and start doing things to make their dream come true. <span><a href="#">View all courses<i class="fa-solid fa-arrow-right"></i></a></span></p>
      </div>
  </div>
</template>

<script>
export default {
    name: "PlanCostComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

#plan-cost{
    margin: 30px 0;
}

#plan-cost-top{
    text-align: center;
    margin: 50px 0;
    h3{
        color: $brand-color;
        font-size: 18px;
    }
    h2{
        font-weight: bold;
    }
}

#plan-cost-middle{
    width: 80%;
    margin: 0 auto;
}

.plan-card{
    width: 25%;
    padding: 0 20px;
    position: relative;
    cursor: pointer;
    img{
        width: 100%;
        border-radius: 5px;
    }
    .basic-info{
        position: absolute;
        bottom: 0px;
        left: 50px;
        width: 70%;
        p:first-child{
            color: $brand-color;
            font-weight: bold;
        }
        p:nth-child(2){
            color: white;
            font-weight: bold;
        }
    }
    .show-on-hover{
        display: none;
    }
}

.plan-card:hover{
    .show-on-hover{
        display: block;
        position: absolute;
        bottom: 0px;
        left: 50px;
        width: 70%;
        p{
            color: white;
            font-weight: bold;
            margin-right: 10px;
            font-size: 14px;
        }
        i{
            font-size: 12px;
            margin-right: 10px;
        }
    }
    .basic-info{
        position: absolute;
        bottom: 110px;
        left: 50px;
        width: 70%;
    }
}

#plan-cost-bottom{
    width: 30%;
    margin: 50px auto;
    text-align: center;
    font-size: 14px;
    a{
        color: rgb(50, 48, 67);
        font-size: 14px;
        i{
            font-size: 12px;
            margin-left: 3px;
        }
    }
}
</style>