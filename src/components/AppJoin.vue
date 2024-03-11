<script>
export default{
    name: 'AppJoin',
}
</script>

<template> 
<div class="container-fluid" id="join">
<div class="mail d-flex align-items-center">
  <div class="container">
    <div class="row w-100 h-100">
      <div class="left col-8  bg-white h-100 bg-transparent text-white">
        <p>Join our mailing list today</p>
        <h2>Insider offers & flash sales in your inbox every week.</h2>
        <div class="">
          <i class="fa-solid fa-chevron-up"></i>
          <i class="fa-solid fa-chevron-up"></i>
          <i class="fa-solid fa-chevron-up"></i>
        </div>
        <input type="email" placeholder="Insert your mail...">
        <button class="btn btn-primary">Subscribe -></button>
        <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
      </div>
    </div>
  </div>
</div>
</div> 
     
</template>

<style lang="scss">
#join{
    background-color: coral;
    height: 730px;

    .mail{
        background-image: url(/public/images/banner1-2x.jpg);
        width: 100%;
        background-color: purple;
        height: 670px;
        background-size: cover;
    }
}
</style>

