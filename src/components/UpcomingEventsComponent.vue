<template>
  <div id="upcoming">
      <div id="upcoming-top">
          <h3>Wanna transform your life?</h3>
          <h2>Upcoming Events</h2>
      </div>
      <div id="upcoming-middle" class="clearfix">
          <div class="upcoming-card">
              <div>
                  <p class="location"><i class="fa-solid fa-location-dot"></i>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div class="d-flex flex-column align-items-center">
                  <p class="number">22</p>
                  <p class="month">NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p class="location"><i class="fa-solid fa-location-dot"></i>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div class="d-flex flex-column align-items-center">
                  <p class="number">22</p>
                  <p class="month">NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p class="location"><i class="fa-solid fa-location-dot"></i>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div class="d-flex flex-column align-items-center">
                  <p class="number">22</p>
                  <p class="month">NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p class="location"><i class="fa-solid fa-location-dot"></i>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div class="d-flex flex-column align-items-center">
                  <p class="number">22</p>
                  <p class="month">NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p class="location"><i class="fa-solid fa-location-dot"></i>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div class="d-flex flex-column align-items-center">
                  <p class="number">22</p>
                  <p class="month">NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p class="location"><i class="fa-solid fa-location-dot"></i>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div class="d-flex flex-column align-items-center">
                  <p class="number">22</p>
                  <p class="month">NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
      </div>
      <div id="upcoming-bottom">
          <p>Excited about our event?<a href="#">View all events<i class="fa-solid fa-arrow-right"></i></a></p>
      </div>
  </div>
</template>

<script>
export default {
    name: "UpcomingEventsComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

#upcoming{
    width: 60%;
    margin: 30px auto;
}

#upcoming-top{
    text-align: center;
    margin: 40px 0;
    h3{
        color: $brand-color;
        font-size: 18px;
    }
    h2{
        font-weight: bold;
    }
}
.clearfix{
    display: table;
    clear: both;
    content: "";
}

#upcoming-middle{
    position: relative;
    z-index: 999;
}

.upcoming-card{
    border-left: 3px solid white;
    width: calc(50% - 30px);
    float: left;
    background-color: rgb(248, 248, 248);
    margin: 15px ;
    padding: 10px;
    display: flex;
    justify-content: space-between;
    i{
        font-size: 12px;
        margin-right: 5px;
    }
    .location{
        font-size: 12px;
        color: grey;
    }
    p:nth-child(2){
        font-weight: bold;
    }
    .number{
        color: $brand-color;
        font-size: 40px;
        margin-bottom: 0.1rem;
    }
    .month{
        font-size: 14px;
        margin-bottom: 0.5rem;
    }
    button{
        padding: 10px 30px;
        color: white;
        font-weight: bold;
        font-size: 12px;
        background-color: $brand-color;
        border: none;
        border-radius: 5px;
    }
    button:hover{
      background-color: rgb(63, 58, 100);
      color: white;
    }
}

.upcoming-card:hover{
    cursor: pointer;
    background-color: white;
    border-left: 3px solid $brand-color;
    border-radius: 5px;
    box-shadow: 0px 0px 4px 0px;
}

#upcoming-bottom{
    text-align: center;
    margin: 40px 0;
    position: relative;
    z-index: 999;
    a{
        color: $brand-color;
        margin-left: 10px;
    }
}
</style>