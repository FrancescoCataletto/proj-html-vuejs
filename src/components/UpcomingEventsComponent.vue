<template>
  <div id="upcoming">
      <div id="upcoming-top">
          <h3>Wanna transform your life?</h3>
          <h2>Upcoming Events</h2>
      </div>
      <div id="upcoming-middle">
          <div class="upcoming-card">
              <div>
                  <p>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div>
                  <p>22</p>
                  <p>NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div>
                  <p>22</p>
                  <p>NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div>
                  <p>22</p>
                  <p>NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div>
                  <p>22</p>
                  <p>NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div>
                  <p>22</p>
                  <p>NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
          <div class="upcoming-card">
              <div>
                  <p>Texas, US</p>
                  <p>Storytelling Workshop</p>
              </div>
              <div>
                  <p>22</p>
                  <p>NOV</p>
                  <button>Get ticket</button>
              </div>
          </div>
      </div>
      <div id="upcoming-bottom">
          <p>Excited about our event?<a href="#">View all evens</a></p>
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
}

.upcoming-card{
    width: calc(50% - 40px);
    float: left;
    background-color: rgb(248, 248, 248);
    margin: 20px;
    padding: 10px;
    display: flex;
    justify-content: space-between;

}

#upcoming-bottom{
    text-align: center;
}
</style>