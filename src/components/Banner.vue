<template>
  <div>
    <div style="margin-top: 20px">
      <div id="demo" class="carousel slide" data-ride="carousel">

        <!-- Indicators -->
        <ul class="carousel-indicators">
            <li data-target="#demo" data-slide-to="0" class="active"></li>
            <li data-target="#demo" data-slide-to="1"></li>
            <li data-target="#demo" data-slide-to="2"></li>
        </ul>

        <!-- The slideshow -->
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="../assets/images/banner1.jpg" alt="Los Angeles">
            </div>
            <div class="carousel-item">
                <img src="../assets/images/banner2.jpg" alt="Chicago">
            </div>
            <div class="carousel-item">
                <img src="../assets/images/banner3.jpg" alt="New York">
            </div>
        </div>

        <!-- Left and right controls -->
        <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#demo" data-slide="next">
            <span class="carousel-control-next-icon"></span>
        </a>

      </div>
    </div>
  </div>
</template>

<script>
export default {
 
}
</script>

<style lang="scss" scoped>
.carousel-inner {
    .carousel-item{
        img {
            height: 350px;
            width: 100%;
        }
    }
}
</style>