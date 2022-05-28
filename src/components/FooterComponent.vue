<template>
  <footer>
      <div id="wrapper">
        <div class="d-flex">
          <div id="address">
            <h3>Address</h3>
            <p>382 NE 191st St # 87394 Miami, FL 33179-3899 +1/305)547-9909(9am - 5pm EST, Monady - Friday)</p>
            <p>support@maxcoach.com</p>
            <div>
              SOCIALS
            </div>
          </div>
          <div id="explore">
            <h3>Explore</h3>
            <div id="left-explore">
              <ul>
                <li>Start here</li>
                <li>Blog</li>
                <li>About us</li>
              </ul>
            </div>
            <div id="right-explore">
              <ul>
                <li>Success story</li>
                <li>Courses</li>
                <li>Contact us</li>
              </ul>
            </div>
          </div>
          <div id="information">
            <h3>Information</h3>
            <ul>
              <li>Membership</li>
              <li>Purchase guide</li>
              <li>Privacy policy</li>
              <li>Terms of service</li>
            </ul>
          </div>
        </div>
        <div id="bottom-wrapper">
          <p>C 2020 Maxcoach. All Rights Reserved</p>
        </div>
      </div>
      <div id="scroll-to-top">
        F
      </div>
  </footer>
</template>

<script>
export default {
    name: "FooterComponent"
}
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
  }
}

#explore{
  width: calc(60% / 2);
}

#left-explore{
  width: 50%;
  float: left;
}

#right-explore{
  width: 50%;
  float: right;
}

#bottom-wrapper{
  text-align: center;
  margin: 30px 0;
}

#scroll-to-top{
  position: absolute;
  bottom: 0;
  right: 0;
}
</style>