<script>
export default{
    name: 'AppJoin',
}
</script>

<template> 
<div class="container-fluid p-0" id="join">
<div class="mail d-flex align-items-center">
  <div class="container">
    <div class="row w-100 h-100">
      <div class="left col-10 bg-white h-100 bg-transparent text-white">
        <h3 class="text-danger">Join our mailing list today</h3>
        <p class="text-desc">Insider offers & flash sales in your inbox every week.</p>
        <div class="mb-4 col-1">
          <img class="img-fluid" src="/public/images/separator-yellow.png" alt="">
        </div>
        <input class="form-control w-50 rounded-pill d-inline-block me-3" type="email" placeholder="Insert your mail...*">
        <button class="my-btn sub-btn btn rounded-pill text-white">Subscribe</button>
        <div class="col-9 mt-3">
          <p class="sub-text">Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur adipiscing elit sed porttitor lectus.</p>
        </div>
      </div>
    </div>
  </div>
</div>
</div> 
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#join{
    background-color: coral;
    height: 730px;

    .mail{
        background-image: linear-gradient(to right, #0d0d0c 35%, transparent 85%), url(/public/images/banner1-2x.jpg);;
        width: 100%;
        height: 100%;
        background-position-x: right;
        background-color: purple;
        background-size: cover;
    }

    input{
      height: 55px;
    }

    h3{
        font-size: 28px;
    }

    .text-desc{
      font-size: 58px;
      line-height: 1.2;
      font-weight: 500;
    }

    .sub-btn{
      padding: 13px 90px;
    }

    .sub-text{
      color:$color3;
      font-size:23px;
    }

}
</style>

