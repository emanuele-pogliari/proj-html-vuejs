<script>
export default{
    name: 'AppHighlighted',
}
</script>

<template> 
<div class="container-fluid p-0" id="highlighted">
    <div class="position-relative section-high">
        <div class="position-absolute top-50 start-50 text-white translate-middle text-center">
            <div><i class="play-btn-big fa-solid fa-play p-5 rounded-circle bg-white"></i></div>
            <div class="fs-1">Crossifit Workout of the day</div>
            <div>November 15th, 2019</div>
            <a href="">View all videos</a>
        </div>
    </div>
</div> 
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;


.container-fluid {
    width: 100%;
    height: 640px; /* Altezza desiderata */
    background-image: linear-gradient(151deg, hsl(234deg 100% 43% / 50%) 0%, hsl(357deg 100% 43% / 50%) 100%), url(/public/images/banner14-2x.jpg), linear-gradient(45deg, black, black);
    background-size: cover;
    background-position: center;
    position: relative;
  }

  .section-high {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-align: center;
  }





// .section-high{
//     background: url('/public/images/banner14-2x.jpg'), linear-gradient(151deg, rgba(255, 0, 0, 0.5) 35%, rgba(0, 0, 255, 0.5) 100%);

//     height: 640px;
//     // background:linear-gradient(151deg, $color4 35%, $color5 100%);
//     // background-image: url('/public/images/banner14-2x.jpg');
//     background-size: cover;
//     mix-blend-mode: multiply;

// }

</style>