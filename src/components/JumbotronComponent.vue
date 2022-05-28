<template>
  <div id="jumbotron">
        <div id="left-jumbo">
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
        <div id="right-jumbo">
          <img src="../assets/img/home-business-hero-avatar.png" alt="">
        </div>
  </div>
</template>

<script>
export default {
    name: "JumbotronComponent"
}
</script>

<style lang="scss" scoped>
#jumbotron{
    height: 724px;
    background-color: rgb(239, 242, 246);
}

#left-jumbo{
  width: 50%;
  height: 100%;
  float: left;
  text-align: center;
}

#right-jumbo{
  width: 50%;
  background-image: url("../assets/img/home-business-hero-global-image.png");
  background-size: contain;
  background-repeat: no-repeat;
  float: right;
}
</style>