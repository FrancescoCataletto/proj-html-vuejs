<template>
  <div id="jumbotron">
        <div id="left-jumbo">
          <div>
            <h3>
            New Challenges, New Skills
            </h3>
            <h1>
            BUILD YOUR OWN LIFE COACHING BUSINESS
            </h1>
            <h5>
            Whole-life Business Coaching for committed entrepreneurs
            </h5>
            <button>Get started today</button>
          </div>
        </div>
        <div id="right-jumbo">
          <div>
            <img src="../assets/img/home-business-hero-avatar.png" alt="">
          </div>
        </div>
  </div>
</template>

<script>
export default {
    name: "JumbotronComponent"
}
</script>

<style lang="scss" scoped>
@import"../assets/img/global.scss";

#jumbotron{
    height: 650px;
    background-color: rgb(239, 242, 246);
}

#left-jumbo{
  width: 50%;
  height: 100%;
  float: left;
  div{
    width: 50%;
    margin-left: 40%;
    margin-top: 20%;
    h1, h3, h5{
      margin: 20px 0;
    }
    h1{
      font-size: 40px;
      color: rgb(51, 51, 51);
      font-weight: bold;
    }
    h3{
      color: $brand-color;
    }
    h5{
      color: rgb(105, 105, 105);
      font-size: 18px;
    }
    button{
      color: white;
      background-color: $brand-color;
      border-radius: 5px;
      border: none;
      padding: 15px 30px;
    }
  }
}

#right-jumbo{
  width: 50%;
  background-image: url("../assets/img/home-business-hero-global-image.png");
  background-size: contain;
  background-repeat: no-repeat;
  float: right;
  div:first-child{
    height: 600px;
    img{
      height: 100%;
      margin-top: 50px;
    }
  }
}
</style>