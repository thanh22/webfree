<template>
  <div id="app" class="background-image">
    <div class="container">
      <Header></Header>
      <Banner></Banner>
      <NewProduct></NewProduct>
      <!-- <div class="d-flex" style="width: 100%">
        <div style="width: 30%">
          <LeftContent></LeftContent>
        </div>
        <div style="width: 70%">
          <RightContent></RightContent>
        </div>
      </div> -->
      <Introduce></Introduce>
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header";
import Banner from "./components/Banner";
import NewProduct from "./components/NewProduct";
import Introduce from "./components/Introduce";
import Footer from "./components/Footer";
import LeftContent from "./components/LeftContent";
import RightContent from "./components/RightContent";
export default {
 components: {
   Header,
   Banner,
   NewProduct,
   Introduce,
   Footer,
   LeftContent,
   RightContent,
 }
}
</script>

<style lang="scss" scoped>
.d-flex {
  display: flex;
}
.background-image {
  background-image: url('./assets/images/background.jpg');
  height: 600px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
