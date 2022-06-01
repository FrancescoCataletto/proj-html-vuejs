<template>
  <footer>
      <div id="wrapper">
        <div class="d-flex">
          <div id="address">
            <h4>Address</h4>
            <p>382 NE 191st St # 87394 Miami, FL 33179-3899 +1/305)547-9909(9am - 5pm EST, Monady - Friday)</p>
            <p>support@maxcoach.com</p>
            <div class="d-flex justify-content-between">
              <i class="fa-brands fa-facebook-square"></i>
              <i class="fa-brands fa-twitter"></i>
              <i class="fa-brands fa-instagram-square"></i>
              <i class="fa-brands fa-linkedin"></i>
            </div>
          </div>
          <div id="explore">
            <h4>Explore</h4>
            <div id="left-explore">
              <ul>
                <li v-for="(rightLink, index) in rightExploreArr" :key="`rightLink${index}`">{{rightLink.link}}</li>
              </ul>
            </div>
            <div id="right-explore">
              <ul>
                <li v-for="(leftLink, index) in leftExploreArr" :key="`leftLink${index}`">{{leftLink.link}}</li>
              </ul>
            </div>
          </div>
          <div id="information">
            <h4>Information</h4>
            <ul>
              <li v-for="(infoLink, index) in informationArr" :key="`infoLink${index}`">{{infoLink.link}}</li>
            </ul>
          </div>
        </div>
        <div id="bottom-wrapper">
          <p><i class="fa-solid fa-copyright"></i> 2020 Maxcoach. All Rights Reserved</p>
        </div>
      </div>
      <div id="scroll-to-top">
        <i class="fa-solid fa-arrow-up"></i>
      </div>
  </footer>
</template>

<script>
export default {
    name: "FooterComponent",

    props:{
      rightExploreArr: Array,
      leftExploreArr: Array,
      informationArr: Array
    }}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

footer{
  background-color: rgb(23, 22, 33);
  color: white;
  position: relative;
}

#wrapper{
  width: 50%;
  margin: 0 auto;
  padding: 50px 0;
}

#address{
  width: 60%;
  p{
    width: 60%;
    color: rgb(149, 149, 150);
    font-size: 12px;
  }
  div{
    margin-top: 50px;
    width: 40%;
    i{
      color: rgb(149, 149, 150);
      cursor: pointer;
      font-size: 24px;
    }
  }
}

#explore{
  width: calc(60% / 2);
  ul{
    padding-left: 0px;
    li{
      list-style: none;
      font-size: 12px;
      margin-bottom: 20px;
      color: rgb(149, 149, 150);
      cursor: pointer;
    }
    li:hover{
      text-decoration: underline;
    }
  }
}

#left-explore{
  width: 50%;
  float: left;
}

#right-explore{
  width: 50%;
  float: right;
}

#information{
  ul{
    padding-left: 0px;
    li{
      cursor: pointer;
      list-style: none;
      font-size: 12px;
      margin-bottom: 20px;
      color: rgb(149, 149, 150);
    }
    li:hover{
      text-decoration: underline;
    }
  }
}

h4{
  margin-bottom: 20px;
}

#bottom-wrapper{
  text-align: center;
  margin: 70px 0 30px 0;
  color: rgb(149, 149, 150);
  font-size: 14px;
}

#scroll-to-top{
  position: absolute;
  bottom: 0;
  right: 0;
  i{
    color: white;
    padding: 25px;
    font-size: 20px;
    margin: 10px;
    border-radius: 50%;
    background-color: $brand-color;
    cursor: pointer;
  }
}
</style>