<template>
  <header class="d-flex justify-content-between align-items-center">
      <div id="left-header">
          <img src="" alt="MaxCoach Logo">
      </div>
      <nav>
          <ul>
              <li>Home</li>
              <li>Pages</li>
              <li>Courses</li>
              <li>Features</li>
              <li>Blog</li>
              <li>Shop</li>
          </ul>
      </nav>
      <div id="right-header" class="d-flex">
          <div>
              <img src="../assets/img/en.png" alt="UK flag">
          </div>
          <input type="text" class="form-control">
      </div>
  </header>
</template>

<script>
export default {
    name: "HeaderComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/img/global.scss";

header{
    height: 80px;
    background-color: bisque;
    width: 100vw;
}

nav{
    width: 40%;
    ul{
        display: flex;
        width: 100%;
        justify-content: space-around;
        li{
            list-style: none;
        }
    }
}
</style>