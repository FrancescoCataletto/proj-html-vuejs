<template>
  <div id="form">
      <div id="circle"></div>
      <div id="wrapper">
        <div id="form-top">
          <div class="d-flex">
            <h2>Subscribe</h2><h2>Newsletters</h2>
          </div>
          <p>Enter your email address to register to our newsletter subscription delivered on a regular basis!</p>
        </div>
        <div id="form-bottom" class="d-flex">
          <input type="email" class="form-control" placeholder="Enter your email">
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
  border: 6px solid rgb(143, 214, 202);
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
  .d-flex{
    justify-content: center;
    h2:first-child{
      font-weight: bold;
      font-size: 40px;
      margin-right: 10px;
      color: rgb(51, 51, 51);
    }
    h2:nth-child(2){
      font-size: 40px;
      color: $brand-color;
    }
  }
  p{
    margin: 20px 0;
  }
}

#form-bottom{
  input{
    background-color: rgb(245, 245, 245);
    padding: 15px 20px;
    border: none;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
  }
  button{
    border: none;
    color: white;
    background-color: $brand-color;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    padding: 0 25px;
    font-size: 14px;
  }
}
</style>