<template>
  <div>
    <div>
      <div class="background-dark-gray"></div>
      <div style="background: rgba(255, 255, 255, 0.85);">
        <div class="d-flex" style="color:white; justify-content: space-between;">
          <div>logo</div>
          <div>
            <div><span class="text-dark">contact</span> </div>
            <div><span class="text-primary">23874293847</span> </div>
          </div>
        </div>
        <nav class="navbar navbar-expand-sm navbar-dark">
        <!-- Links -->
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">About Us</a>
          </li>
          <!-- Dropdown -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle text-dark" href="#" id="navbardrop" data-toggle="dropdown">
              Product
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item text-dark" href="#">Link 1</a>
              <a class="dropdown-item text-dark" href="#">Link 2</a>
              <a class="dropdown-item text-dark" href="#">Link 3</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">News</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Correction</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Safety Note</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Contact us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Career</a>
          </li>
        </ul>
      </nav>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
 
}
</script>

<style lang="scss" scoped>
.background-dark-gray {
  background: #333333;
  width: 100%;
  height: 20px;
}
.d-flex {
  display: flex;
}
.navbar {
  .navbar-nav {
    .nav-item {
      min-width: 150px;
      text-align: center;
    }
  }
}
</style>