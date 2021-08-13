<template>
  <div style="margin-top: 30px">
    <div class="owl-carousel owl-theme">
      <div class="item">
        <div class="area-name">product 1</div>
        <div class="area-link">
          <a href="#">
            <i class="fas fa-chevron-right"></i>
          </a>
        </div>
        <img src="../assets/images/product1.jpg" alt="">
        
      </div>
      <div class="item">
        <div class="area-name">product 2</div>
        <div class="area-link">
          <a href="#">
            <i class="fas fa-chevron-right"></i>
          </a>
        </div>
        <img src="../assets/images/product2.jpg" alt="">
      </div>
      <div class="item">
        <div class="area-name">product 3</div>
        <div class="area-link">
          <a href="#">
            <i class="fas fa-chevron-right"></i>
          </a>
        </div>
        <img src="../assets/images/product3.jpg" alt="">
      </div>
      <div class="item">
        <div class="area-name">product 4</div>
        <div class="area-link">
          <a href="#">
            <i class="fas fa-chevron-right"></i>
          </a>
        </div>
        <img src="../assets/images/product4.jpg" alt="">
      </div>
      <div class="item">
        <div class="area-name">product 5</div>
        <div class="area-link">
          <a href="#">
            <i class="fas fa-chevron-right"></i>
          </a>
        </div>
        <img src="../assets/images/product5.jpg" alt="">
      </div>
    </div>
    <div style="margin-top: 20px">
      <span style="font-size: 12px; line-height: 0">
        SHAKO CO., LTD. was founded in 1980, and is now Taiwan's leading manufacturer of pneumatic components. 
        Our product range includes FRL combination, pneumatic solenoid valves, pneumatic valves, pneumatic cylinders,
        mechanical valves, pneumatic press and other relevant valves and accessories. All the product series have 
        been widely applied to the industrial fields of automation equipment, automotive assembly, medication and 
        electronic machinery. Adhering to the business idea of "Customer First", we have established 
        a robust sales network and satisfied after-sale service.
      </span>
      <div style="text-align: center; margin-top: 40px;">
        <button class="btn-more">MORE</button>
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
 
}
</script>

<style lang="scss" scoped>
.area-name {
  position: absolute;
  margin-top: 20px;
  height: 40px;
  background: rgba(255, 255, 255, 0.3);
  width: 100%;
  text-align: center;
  line-height: 2.5;
}
.item {
  position: relative;
}
.area-link {
  position: absolute;
  bottom: 0;
  right: 0;
  width: 40px;
  height: 40px;
  background: #00A0EA;
    text-align: center;
    line-height: 2.5;
  a {
    text-decoration: none;
    color: white;
  }
}
.btn-more {
  border: 3px solid #00A0EA; 
  color: #00A0EA; 
  font-size: 18px; 
  background: none; 
  padding: 5px 25px;
}
</style>