<script>
import {store} from '../store.js';
import AppNavLinks from './AppNavLinks.vue';

export default{
    name: 'AppHeader',

    components: {
      AppNavLinks,
    },
    data() {
      return {
        store,
      }
    },
}
</script>


<template>
<nav class="navbar navbar-expand-lg bg-black" data-bs-theme="dark">
  <div class="container p-0">
    <a class="navbar-brand" href="#"><img src="/public/images/logo.png" alt=""></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
      <ul class="navbar-nav mb-2 mb-lg-0 d-flex gap-4 align-items-center">
        <AppNavLinks v-for="link in store.navLinks" :links="link"></AppNavLinks>
        <li class="nav-item">
          <a class="nav-link" href="#">Store <span class="badge ms-2 rounded-1 py-1 ">new</span></a>
        </li>
        <li class="nav-item">
          <button class="btn btn-nav rounded-pill text-white">Schedule a workout</button>
        </li>
        <i class="fa-solid fa-cart-shopping text-white align-items-start "></i>
        <i class="fa-solid fa-magnifying-glass text-white align-items-center"></i>
      </ul>
    </div>
  </div>
</nav>
<div class="jumbotron d-flex align-items-center">
  <div class="container p-0">
    <div class="row w-100 h-100 d-flex align-items-center">
      <div class="left col-8 p-0  bg-white  bg-transparent text-white">
        <p class="text-1">Certified fitness professional</p>
        <h2 class="text-2 mb-4">Take control of your health</h2>
        <div class="mb-4 col-1">
          <img class="img-fluid" src="/public/images/separator-yellow.png" alt="">
        </div>
          <p class="mb-5">Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
        <button class="btn my-btn rounded-pill me-2"><i class="me-2 fa-brands fa-youtube"></i>Visit my youtube channel</button>
        <button class="btn bg-black rounded-pill">Buy Avada today -></button>
      </div>
      <div class="right col-4 text-center h-100 text-white">
        <i class="play-btn-big fa-solid fa-play p-5 rounded-circle bg-white"></i>
      </div>
    </div>
  </div>
</div>
</template>
<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
.navbar{
    height: 100px;
    .badge{
      background-color: $color6;
      color: $color1;
    }
    .btn-nav{
      font-size:14px;
      padding: 13px 29px;
      line-height: 17px;
      background-color: $color4;
    }

}
.jumbotron{
  background-image: url(/public/images/slider82x-scaled.jpg);
    width: 100%;
    height: 670px;
    background-size: cover;
    
    

    .text-1{
      font-size:27px;
      color:$color5;
    }

    .text-2{
      font-size:75px;
      color:white;
    }




  }

</style>