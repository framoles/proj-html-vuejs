<template>
  <div class="container">
    <div class="cont-up d-flex">
      <div class="left">
        <div class="big-posts">
          <div class="post">
            <img src="../assets/img/blog-54.jpg" alt="blog-54" />
            <div class="post-info d-flex">
              <div class="date d-flex">
                <span class="day">12</span>
                <span class="month">JAN</span>
              </div>
              <div class="overview">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Aliquid, eum, impedit nihil vero hic dolorem dolorum maiores
                quaerat neque voluptatibus earum est optio asperiores quis sint,
                id quod delectus amet.
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="right">instagram</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PostView",
};
</script>
<style lang="scss" scoped>
@import "../style/general.scss";
.cont-up {
  padding: 50px 0;
  column-gap: 30px;
  .left {
    width: 80%;
    .big-posts {
      .post {
        img {
          width: 100%;
          margin-bottom: 10px;
        }
        .post-info {
          .date {
            margin-right: 10px;
            flex-direction: column;
            padding: 10px;
            .day {
              background-color: $white-grey;
              color: black;
              text-align: center;
              font-size: 13px;
              font-weight: 800;
            }
            .month {
              color: white;
              background-color: black;
              text-align: center;
              padding: 10px;
              font-size: 10px;
            }
          }
        }
      }
    }
  }
  .right {
    width: 20%;
  }
}
</style>