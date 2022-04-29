<template>
  <div>
    <footer class="up">
      <div class="container d-flex">
        <div class="about">ABOUT</div>
        <div class="recent-post">RECENT POST</div>
        <div class="recent-comment">RECENT COMMENT</div>
      </div>
    </footer>
    <footer class="down">
      <div class="container d-flex">
        <div class="left d-flex">
          <img src="../assets/img/logo-footer.png" alt="logo footer" />
          <span>Copyright 2020 All right reserved</span>
        </div>
        <div class="right d-flex">
          <ul class="d-flex">
            <li>Site Map</li>
            <li>Site Map</li>
            <li>Site Map</li>
          </ul>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

scss-<style lang="scss" scoped>
@import "../style/general.scss";
div {
  .up {
    background-color: #212529;
    text-align: center;
  }
  .down {
    .container {
      justify-content: space-between;
    }
    text-align: center;
    background-color: #1c2023;
    padding: 30px 0;
    .left {
      align-items: center;
      img {
        width: 70px;
        margin-right: 40px;
      }
      span {
        color: $white;
        font-size: 12px;
        color: #777777;
      }
    }
    .right {
      align-items: center;
      ul {
        column-gap: 20px;
        li {
          list-style: none;
          color: #777777;
          font-size: 12px;
        }
      }
    }
  }
}
</style>