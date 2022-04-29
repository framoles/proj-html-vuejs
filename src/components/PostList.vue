<template>
  <div class="container">
    <div id="postlist">
      <div class="d-flex">
        <!-- Popular posts -->
        <div class="popular post">
          <p class="title">POPULAR POSTS</p>
          <!-- 1 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-55.jpg" alt="blog-55" />
            <div class="box-info">
              <p class="overview">Simplay Way to Have a Pretty Face</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 2 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-56.jpg" alt="blog-56" />
            <div class="box-info">
              <p class="overview">Ranking the greatest players in basketball</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 3 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-57.jpg" alt="blog-57" />
            <div class="box-info">
              <p class="overview">4 Ways to Look Cool in Glasses</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 4 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-58.jpg" alt="blog-58" />
            <div class="box-info">
              <p class="overview">Top Camper Trailer Towing Tips</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 5 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-59.jpg" alt="blog-59" />
            <div class="box-info">
              <p class="overview">5 Lovely Walks in New York</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
        </div>
        <!-- recent posts -->
        <div class="recent post">
          <p class="title">RECENT POSTS</p>
          <!-- 1 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-65.jpg" alt="blog-65" />
            <div class="box-info">
              <p class="overview">Main Reasons To Stop Texting and Driving</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 2 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-66 (1).jpg" alt="blog-66" />
            <div class="box-info">
              <p class="overview">
                Tips to help You Quickly Prepare your Lounch
              </p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 3 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-67.jpg" alt="blog-67" />
            <div class="box-info">
              <p class="overview">Why should I buy a smartwhatch?</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 4 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-68.jpg" alt="blog-68" />
            <div class="box-info">
              <p class="overview">The best augmented reality smartglasses</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
          <!-- 5 post -->
          <div class="single-post d-flex">
            <img src="../assets/img/blog-69.jpg" alt="blog-69" />
            <div class="box-info">
              <p class="overview">12 Healthiest Foods to Eat for Breakfast</p>
              <p class="date">January 12, 2019</p>
            </div>
          </div>
        </div>
        <div class="featured post">
          <p class="title">FEATURED POSTS</p>
          <div class="f-img">
            <div class="info">
              <span>RECIPES</span>
              <p>Tips to Help You Quickly Prepare your Lunch</p>
            </div>
            <img src="../assets/img/blog-66.jpg" alt="blog-66" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PostList",
};
</script>

<style lang="scss" scoped>
@import "../style/general.scss";
#postlist {
  padding: 50px 0;
}
.container {
  background-color: $white;
  .post {
    width: calc(100% / 3);
    .title {
      font-size: 13px;
      font-weight: 800;
      color: $nav-grey;
    }
    .single-post {
      margin-top: 20px;
      img {
        width: 50px;
      }
      .box-info {
        margin-left: 15px;
        .overview {
          font-size: 15px;
          color: $dark-grey;
        }
        .date {
          font-size: 12px;
          color: #777777;
          margin-top: 5px;
        }
      }
    }
  }
  .featured {
    .f-img {
      margin-top: 25px;
      position: relative;
      width: 100%;
      img {
        height: 200px;
        width: 94%;
      }
      .info {
        position: absolute;
        bottom: 25px;
        left: 25px;
        color: $white;
        width: 100%;
        span {
          background-color: $bg-blue;
          padding: 5px;
          border-radius: 2px;
          margin-bottom: 10px;
          font-size: 11px;
          font-weight: bold;
        }
        p {
          font-size: 20px;
          font-weight: bold;
        }
      }
    }
  }
}
</style>