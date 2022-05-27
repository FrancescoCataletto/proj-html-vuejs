<template>
  <div id="plan-cost">
      <div id="plan-cost-top">
          <h3>Let's Dream Big Together</h3>
          <h2>Explore How Can I help you</h2>
      </div>
      <div id="plan-cost-middle" class="d-flex">
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div>
                  <p>$40.00</p>
                  <p>Learning to Write as  Professional Author</p>
              </div>
          </div>
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div>
                  <p>$40.00</p>
                  <p>Learning to Write as  Professional Author</p>
              </div>
          </div>
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div>
                  <p>$40.00</p>
                  <p>Learning to Write as  Professional Author</p>
              </div>
          </div>
          <div class="plan-card">
              <img src="../assets/img/course-02-443x600.jpg" alt="">
              <div>
                  <p>$40.00</p>
                  <p>Learning to Write as  Professional Author</p>
              </div>
          </div>
      </div>
      <div id="plan-cost-bottom">
          <p>Take the control of their life back and start doing things to make their dream come true. <span><a href="#">View all courses</a></span></p>
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
    h3{
        margin-bottom: 30px;
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
    img{
        width: 100%;
    }
    div{
        position: absolute;
        bottom: 0px;
        left: 50px;
    }
}

#plan-cost-bottom{
    width: 50%;
    margin: 30px auto;
    text-align: center;
}
</style>