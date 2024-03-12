<script>
export default{
    name: 'AppTraining',
}
</script>

<template> 
<div id="training">
    <div class="container">
        <div class="cards row text-white d-flex flex-row justify-content-between">
            <div class="single-card rounded-2  text-center">
            <div class="mb-3 mx-auto my-icon">
                <img class="img-fluid w-100 h-100" src="/public/images/smartwatch.png" alt="">
            </div>
            <p class="mb-0 card-title">Team training</p>
            <small class="sub-title">Find a partner</small>
            <p class="my-text">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
            <a href="">Find a partner</a><i class="fa-solid fa-chevron-right"></i>
        </div>
        <div class="single-card rounded-2 text-center">
            <div class="mb-3 mx-auto my-icon"><img class="img-fluid w-100 h-100" src="/public/images/gym.png" alt=""></div>
            <p class="mb-0 card-title">Crossifit workout</p>
            <small class="sub-title">Push your limits</small>
            <p class="my-text">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
            <a href="">Learn about crossfit</a><i class="fa-solid fa-chevron-right"></i> 
        </div>
        <div class="single-card rounded-2 text-center">
            <div class="mb-3 mx-auto my-icon">
                <img class="img-fluid w-100 h-100" src="/public/images/weight-loss.png" alt="">
            </div>
            <p class="mb-0 card-title">Weight loss plan</p>
            <small class="sub-title">Shed those pounds</small>
            <p class="my-text">At laoreet senectus volutpat diam vel sed sed amet pellentesque. Lobortis ut aliquam risus purus. A tellus ut etiam.</p>
            <a href="">Schedule a workout</a><i class="fa-solid fa-chevron-right"></i>
        </div>
    </div>
</div> 
</div>
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#training{
    background-color: black;

    .cards{
        padding-top: 110px;
        padding-bottom: 120px;
        gap:50px;
    }

    .single-card{
        width:calc(100% / 3 - 30px * 3 / 2);
        padding: 70px 40px;
        border: 5px solid $color4;

        .card-title{
            font-size:28px;
        }
        
        .sub-title{
            font-size: 24px;
            color: $color6;
        }

        .fa-chevron{
            font-size:8px;
            margin-left: 10px;
        }

    }

    .my-text{
        margin-top:50px;
        margin-bottom: 45px;
        font-size:19px;
        color:#d5d4d7;
    }

    .my-icon{
        width:80px;
        height: 80px;
        margin-bottom: 35px;
    }
}
</style>