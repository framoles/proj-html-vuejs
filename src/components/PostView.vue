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
                <h2>How To Make Friends as a GrowUp</h2>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Aliquid, eum, impedit nihil vero hic dolorem dolorum maiores
                  quaerat neque voluptatibus earum est optio asperiores quis
                  sint, id quod delectus amet. Lorem ipsum dolor sit amet
                  consectetur adipisicing elit. Aliquid, eum, impedit nihil vero
                  hic dolorem dolorum maiores quaerat neque voluptatibus earum
                  est optio asperiores quis sint, id quod delectus amet.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="big-posts">
          <div class="post">
            <img src="../assets/img/blog-55 (1).jpg" alt="blog-54" />
            <div class="post-info d-flex">
              <div class="date d-flex">
                <span class="day">12</span>
                <span class="month">JAN</span>
              </div>
              <div class="overview">
                <h2>How To Make Friends as a GrowUp</h2>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Aliquid, eum, impedit nihil vero hic dolorem dolorum maiores
                  quaerat neque voluptatibus earum est optio asperiores quis
                  sint, id quod delectus amet. Lorem ipsum dolor sit amet
                  consectetur adipisicing elit. Aliquid, eum, impedit nihil vero
                  hic dolorem dolorum maiores quaerat neque voluptatibus earum
                  est optio asperiores quis sint, id quod delectus amet.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="big-posts">
          <div class="post">
            <img src="../assets/img/blog-56 (1).jpg" alt="blog-54" />
            <div class="post-info d-flex">
              <div class="date d-flex">
                <span class="day">12</span>
                <span class="month">JAN</span>
              </div>
              <div class="overview">
                <h2>How To Make Friends as a GrowUp</h2>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Aliquid, eum, impedit nihil vero hic dolorem dolorum maiores
                  quaerat neque voluptatibus earum est optio asperiores quis
                  sint, id quod delectus amet. Lorem ipsum dolor sit amet
                  consectetur adipisicing elit. Aliquid, eum, impedit nihil vero
                  hic dolorem dolorum maiores quaerat neque voluptatibus earum
                  est optio asperiores quis sint, id quod delectus amet.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="big-posts">
          <div class="post">
            <img src="../assets/img/blog-58 (1).jpg" alt="blog-54" />
            <div class="post-info d-flex">
              <div class="date d-flex">
                <span class="day">12</span>
                <span class="month">JAN</span>
              </div>
              <div class="overview">
                <h2>How To Make Friends as a GrowUp</h2>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Aliquid, eum, impedit nihil vero hic dolorem dolorum maiores
                  quaerat neque voluptatibus earum est optio asperiores quis
                  sint, id quod delectus amet. Lorem ipsum dolor sit amet
                  consectetur adipisicing elit. Aliquid, eum, impedit nihil vero
                  hic dolorem dolorum maiores quaerat neque voluptatibus earum
                  est optio asperiores quis sint, id quod delectus amet.
                </p>
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
.container {
  background-color: $white;
}
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
          margin: 30px 0 60px 0;
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
              padding: 20px 5px;
            }
            .month {
              color: white;
              background-color: black;
              text-align: center;
              padding: 10px;
              font-size: 10px;
            }
          }
          .overview {
            h2 {
              margin-bottom: 20px;
            }
            p {
              font-size: 14px;
              color: #b7b7b7;
              line-height: 30px;
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