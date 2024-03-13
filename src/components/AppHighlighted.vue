<script>
export default{
    name: 'AppHighlighted',
}
</script>

<template> 
<div class="container-fluid p-0" id="highlighted">
    <div class="position-relative section-high">
        <div class="text-container accordion position-absolute top-50 start-50 text-white translate-middle text-center d-flex flex-column">
            <div><i class="play-btn-big fa-solid fa-play"></i></div>
            <h5 class="video-title">Crossifit Workout of the day</h5>
            <small class="date">November 15th, 2019</small>
            <a>View all videos <span class="align-middle ">&#8594;</span></a>
        </div>
    </div>
</div> 
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;


.container-fluid {
    width: 100%;
    height: 640px; /* Altezza desiderata */
    background-image: linear-gradient(151deg,$color4 20%, $color5 100%), url(/public/images/banner14-2x.jpg);
    background-size: cover;
    background-blend-mode: multiply;
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

    .play-btn-big{
        padding: 34px 38px;
        max-width: 88px;
        max-height: 88px;
        margin-bottom: 1.3em;
        
    }
    
    .video-title{
        font-size: 58px;
    
    }

    .date{
        font-size: 38px;
        color:$color6;
    }
    

    a{
        font-size: 20px;
    }


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