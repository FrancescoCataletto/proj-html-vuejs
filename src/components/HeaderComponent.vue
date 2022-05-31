<template>
  <header class="d-flex align-items-center">
      <div id="left-header" class="d-flex justify-content-center">
          <a href="#"><img src="../assets/img/dark-logo.png" alt="MaxCoach Logo"></a>
      </div>
      <nav>
          <ul>
              <li>Home<i class="fa-solid fa-chevron-down"></i></li>
              <li>Pages<i class="fa-solid fa-chevron-down"></i></li>
              <li>Courses<i class="fa-solid fa-chevron-down"></i></li>
              <li>Features<i class="fa-solid fa-chevron-down"></i></li>
              <li>Blog<i class="fa-solid fa-chevron-down"></i></li>
              <li>Shop<i class="fa-solid fa-chevron-down"></i></li>
          </ul>
      </nav>
      <div id="right-header" class="d-flex">
          <div class="d-flex">
              <img v-if="value==='en'" src="../assets/img/en.png" alt="UK flag">
              <img v-else src="../assets/img/de.png" alt="DE flag">
              <select name="" id="" v-model="value">
                  <option value="en" selected>ENGLISH</option>
                  <option value="de">GERMAN</option>
              </select>
              <i class="fa-solid fa-circle-user"></i>
          </div>
          <input type="text" class="form-control" placeholder="Search..."><i class="fa-solid fa-magnifying-glass"></i>
      </div>
  </header>
</template>

<script>
export default {
    name: "HeaderComponent",
    data(){
        return{
            value: "en"
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

header{
    background-color: white;
    height: 70px;
    width: 100%;
}

#left-header{
    width: 25%;
    float: left;
    img{
        height: 25px;
    }
}

nav{
    float: left;
    width: 50%;
    ul{
        display: flex;
        width: 80%;
        margin: 0 auto;
        justify-content: space-around;
        li{
            list-style: none;
            display: flex;
            align-items: center;
            cursor: pointer;
            i{
                font-size: 8px;
                margin-left: 5px;
                cursor: pointer;
            }
        }
    }
}

#right-header{
    float: right;
    width: 25%;
    position: relative;
    div{
        height: 70px;
        width: 100%;
        justify-content: space-around;
        img{
            margin: auto 0;
            height: 25px;
            cursor: pointer;
        }
        .fa-circle-user{
            line-height: 70px;
            cursor: pointer;
        }
    }
    select{
        border: none;
    }
    input{
        height: 70px;
        border: none;
        border-radius: 0;
        border-left: 1px solid lightgrey;
    }
}

.fa-magnifying-glass{
    cursor: pointer;
    position: absolute;
    right: 10px;
    top: 30px;
}
</style>