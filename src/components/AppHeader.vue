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
          <a class="nav-link" href="#">Store</a>
        </li>
        <li class="nav-item">
          <button class="btn btn-primary rounded-3">Schedule a workout</button>
        </li>
        <i class="fa-solid fa-cart-shopping"></i>
        <i class="fa-solid fa-magnifying-glass"></i>
      </ul>
    </div>
  </div>
</nav>
<div class="jumbotron">
    <!-- <img class="img-fluid" src="/images/slider82x-scaled.jpg" alt=""> -->
</div>
</template>
<style lang="scss">
.navbar{
    height: 100px;
}

.jumbotron{
    width: 100%;
    background-color: purple;
    height: 500px;
}

</style>