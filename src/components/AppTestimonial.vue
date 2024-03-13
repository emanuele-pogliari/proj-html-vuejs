<script>
export default{
    name: 'AppTestimonial',
}
</script>

<template> 
<div class="container-fluid" id="testimonial">

<div class="container testimonial-container d-flex align-items-center justify-content-center ">
    <div class="row w-100 h-100 text-center align-items-center justify-content-center">
      <div class="left col-9 m-auto bg-white h-100 bg-transparent text-white">
        <p class="quote">"I've failed over and over again in my life. And that is why I succeed."</p>
        <div class="mb-4 col-2 mx-auto">
          <img class="separator-y" src="/images/separator-yellow.png" alt="">
        </div>
          <p class="demo-text">Arcu auctor gravida nisl, congue sit nisi tincidunt eget proin. In lacinia lacus donec sed massa in ipsum eros, tristique. Gravida suspendisse etiam in iaculis</p>
        <button class="btn my-btn buy-btn rounded-pill"><a>Buy Avada today <i class="ms-1 fa-solid fa-angle-right"></i></a></button>
      </div>
    </div>
</div>


</div> 
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#testimonial{
    height: 775px;
    background-image: linear-gradient(180deg, hsla(240, 8%, 3%, calc(100% - 84%)) 0%, #060607 100%), url(/public/images/banner2-2x.jpg);
    width: 100%;
    background-size: cover;
    background-position: center;
    padding-top: 185px;

.quote{
  font-size: 58px;
  font-weight: 500;
}

.my-btn{
  line-height: 21px;
}

.demo-text{
  font-size: 23px;
  color: #D6D5D8BF;
  margin-bottom: 30px;
  
}

.separator-y{
  width: 70px;
}

.buy-btn{
  background-color: $color4;
  &:hover{
    background-color: $color2;
  }  
}
}
    
</style>

