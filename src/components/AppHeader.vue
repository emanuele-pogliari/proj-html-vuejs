<script>
export default{
    name: 'AppHeader',
}
</script>


<template>
<nav class="navbar navbar-expand-lg bg-black" data-bs-theme="dark">
  <div class="container">
    <a class="navbar-brand" href="#"><img src="/public/images/logo.png" alt=""></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
      <ul class="navbar-nav mb-2 mb-lg-0 d-flex gap-4">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#"></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Videos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Blog</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Store <span class="badge text-bg-secondary">new</span></a>
        </li>
        <li class="nav-item">
          <button class="btn btn-primary rounded-3">Schedule a workout</button>
        </li>
        <i class="fa-solid fa-cart-shopping text-white align-items-center"></i>
        <i class="fa-solid fa-magnifying-glass text-white align-items-center"></i>
      </ul>
    </div>
  </div>
</nav>
<div class="jumbotron d-flex align-items-center">
  <div class="container">
    <div class="row w-100 h-100">
      <div class="left col-8  bg-white h-100 bg-transparent text-white">
        <p>Certified fitness professional</p>
        <h2>Take control of your health</h2>
        <div class="">
          <i class="fa-solid fa-chevron-up"></i>
          <i class="fa-solid fa-chevron-up"></i>
          <i class="fa-solid fa-chevron-up"></i>
        </div>
          <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
        
        <button class="btn btn-primary">Visit my youtube channel</button>
        <button class="btn btn-primary">Buy Avada today -></button>
      </div>
      <div class="right col-4 text-center bg-black h-100 text-white">Right side</div>
    </div>
  </div>
</div>
</template>
<style lang="scss">
.navbar{
    height: 100px;
}

.jumbotron{
  background-image: url(/public/images/slider82x-scaled.jpg);
    width: 100%;
    background-color: purple;
    height: 670px;
    background-size: cover;
  }

</style>