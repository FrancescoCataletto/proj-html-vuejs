<template>
  <header class="d-flex align-items-center">
      <div id="left-header" class="d-flex justify-content-center">
          <a href="#"><img src="../assets/img/dark-logo.png" alt="MaxCoach Logo"></a>
      </div>
      <nav>
          <ul>
              <li v-for="(link, index) in navArr" :key="`link${index}`">{{link.link}}<i class="fa-solid fa-chevron-down"></i></li>
          </ul>
      </nav>
      <div id="right-header" class="d-flex">
          <div class="d-flex">
              <img :src="this.lingua[this.index].flag" alt="UK flag">
              <select name="" id="" v-model="value" @change="language">
                  <option value="en" selected>{{this.lingua[0].language}}</option>
                  <option value="de">{{this.lingua[1].language}}</option>
                  <option value="fr">{{this.lingua[2].language}}</option>
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

    props:{
        lingua: Array,
        navArr: Array
    },

    data(){
        return{
            value: "en",
            index: 0
        }
    },

    methods:{
        language(){
            if(this.value === "de"){
               this.index = 1
            }else if(this.value === "fr"){
               this.index = 2
            }else{
                this.index = 0
            }
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