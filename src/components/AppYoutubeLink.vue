<script>
export default{
    name: 'AppYoutubeLink',
}
</script>

<template> 
<div class="container-fluid p-0" id="youtube">
    <div class="row h-100">
        <div class="left col-6">
            <img class="img-fluid" src="/public/images/service15-2x.jpg" alt="">
        </div>
        <div class="rightr col-6 p-5">
            <div>Tune up your workouts</div>
            <h3>The best health & fitness advice online</h3>
            <p>Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
            <button class="btn btn-danger">Visit my Youtube channel</button>
        </div>
    </div>
</div> 
     
</template>

<style scoped lang="scss">
#youtube{
    height: 805px;

    .left{
        height:100%;
        transform: translateY(-60px);
        
        
    }

    img{
        width: 100%;
        height: 100%;
        border-radius: 4px;
        border-bottom-right-radius: 40px;
        object-fit: cover;
        overflow: hidden;
    }
}

</style>