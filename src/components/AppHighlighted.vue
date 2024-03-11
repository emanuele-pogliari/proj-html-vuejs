<script>
export default{
    name: 'AppHighlighted',
}
</script>

<template> 
<div class="container-fluid p-0" id="highlighted">
    <div class="img-section position-relative ">
        <img src="/public/images/banner14-2x.jpg" class="img-fluid" alt="">
        <div class="position-absolute top-50 start-50 text-white translate-middle-x text-center">
            <div>play</div>
            <div class="fs-1">Crossifit Workout of the day</div>
            <div>November 15th, 2019</div>
            <a href="">View all videos</a>
        </div>
    </div>
</div> 
     
</template>

<style lang="scss">
#highlighted{
    height: 640px;
    
    .img-section{
        width: 100%;
        height: 100%;
        filter: linear-gradient(151deg, #4154ff 35%, #ff414b 100%); 
    }
}
</style>