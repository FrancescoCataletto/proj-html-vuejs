<template>
  <div id="form">
      <div id="circle"></div>
      <div id="wrapper">
        <div id="form-top">
          <h2>Subscribe<span>Newsletters</span></h2>
          <h3>Enter your email address to register to our newsletter subscription delivered on a regular basis!</h3>
        </div>
        <div id="form-bottom" class="d-flex">
          <input type="text" class="form-control">
          <button>Subscribe</button>
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "FormComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";
#form{
  background-image: url("../assets/img/maxcoach-shape-09.png"), url("../assets/img/maxcoach-shape-02.png");
  background-repeat: no-repeat;
  background-position: top 0 right 400px, top 75px right 410px;
  position: relative;
}

#circle{
  position: absolute;
  padding: 20px;
  border: 6px solid green;
  border-radius: 50%;
  top: 50%;
  left: 15%;
  transform: translate(-50%, -50%);
  opacity: 0.6;
}

#wrapper{
  width: 30%;
  margin: 70px auto;
}

#form-top{
  text-align: center;
  margin-bottom: 50px;
}
</style>