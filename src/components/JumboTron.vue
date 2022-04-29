<template>
  <div class="container">
    <div class="d-flex wrap">
      <!-- pic1 -->
      <div class="picture">
        <div class="pic-info">
          <div class="go-down">
            <div class="category"><span>PHOTOGRAPHY</span></div>
            <p class="overview">
              How to take Better Concert Picture in 30 Seconds
            </p>
          </div>
        </div>
        <img src="../assets/img/blog-46.jpg" alt="img" />
      </div>
      <!-- pic2 -->
      <div class="picture">
        <div class="pic-info">
          <div class="go-down">
            <div class="category"><span>GADGETS</span></div>
            <p class="overview">
              Gadgets That Make Your Smartphone Even Smarter
            </p>
          </div>
        </div>
        <img src="../assets/img/blog-47.jpg" alt="img" />
      </div>
      <!-- pic3 -->
      <div class="picture">
        <div class="pic-info">
          <div class="go-down">
            <div class="category"><span>TRAVEL</span></div>
            <p class="overview">
              20 Top-Rated Tourist Attractions in Manhattan
            </p>
          </div>
        </div>
        <img src="../assets/img/blog-48.jpg" alt="img" />
      </div>
      <!-- pic4 -->
      <div class="picture">
        <div class="pic-info">
          <div class="go-down">
            <div class="category"><span>LIFESTYLE</span></div>
            <p class="overview">The Best Way to Ride a Motorcycle</p>
          </div>
        </div>
        <img src="../assets/img/blog-49.jpg" alt="img" />
      </div>
      <!-- pic5 -->
      <div class="picture">
        <div class="pic-info">
          <div class="go-down">
            <div class="category"><span>TRAVEL</span></div>
            <p class="overview">5 Fun Things to Do at the Beach</p>
          </div>
        </div>
        <img src="../assets/img/blog-50.jpg" alt="img" />
      </div>
      <!-- pic6 -->
      <div class="picture">
        <div class="pic-info">
          <div class="go-down">
            <div class="category"><span>RECIPES</span></div>
            <p class="overview">
              Amazingly Fresh Fruit And Herb Drink For Summer
            </p>
          </div>
        </div>
        <img src="../assets/img/blog-51.jpg" alt="img" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "JumboTron",
};
</script>

<style lang="scss" scoped>
@import "../style/general.scss";
.d-flex {
  gap: 30px;
  padding: 50px 0;
}

.picture {
  position: relative;
  width: calc(100% / 3 - 30px);
  img {
    width: 100%;
    height: 100%;
  }
  .pic-info {
    background-color: #1c202365;
    color: $white;
    position: absolute;
    height: 100%;
    width: 100%;
    .category {
      margin-bottom: 10px;
      font-size: 11px;
      font-weight: bold;
      span {
        background-color: $bg-blue;
        padding: 5px;
        border-radius: 2px;
      }
    }
    .overview {
      font-size: 20px;
      font-weight: bold;
    }
    .go-down {
      position: absolute;
      bottom: 0;
      padding: 25px;
    }
  }
  &:hover {
    outline: 5px solid $white;
    transition: 200ms;
  }
}
</style>