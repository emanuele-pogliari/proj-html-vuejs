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
            <div class="card-wrapper">
                <div class="mb-3 mx-auto my-icon">
                    <img class="img-fluid w-100 h-100" src="/images/smartwatch.png" alt="">
                </div>
                <p class="mb-0 card-title">Team training</p>
                <small class="sub-title">Find a partner</small>
                <p class="my-text">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
                <a href="">Find a partner</a><i class="ms-1 fa-solid fa-angle-right"></i>
            </div>
        </div>
        <div class="single-card rounded-2 text-center">
            <div class="card-wrapper">
            <div class="mb-3 mx-auto my-icon"><img class="img-fluid w-100 h-100" src="/images/gym.png" alt=""></div>
            <p class="mb-0 card-title">Crossifit workout</p>
            <small class="sub-title">Push your limits</small>
            <p class="my-text">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
            <a href="">Learn about crossfit</a><i class="ms-2 fa-solid fa-angle-right"></i> 
        </div>
        </div>
        <div class="single-card rounded-2 text-center">
            <div class="card-wrapper">
            <div class="mb-3 mx-auto my-icon">
                <img class="img-fluid w-100 h-100" src="/images/weight-loss.png" alt="">
            </div>
            <p class="mb-0 card-title">Weight loss plan</p>
            <small class="sub-title">Shed those pounds</small>
            <p class="my-text">At laoreet senectus volutpat diam vel sed sed amet pellentesque. Lobortis ut aliquam risus purus. A tellus ut etiam.</p>
            <a href="">Schedule a workout</a><i class="ms-1 fa-solid fa-angle-right"></i>
            </div>
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
        gap:25px;
    }

    .single-card{
        width:calc(100% / 3 - 25px * 3 / 2);
        height:555px;
        padding: 70px 30px;
        border: 5px solid $color4;
        position: relative;
        transition: transform 0.35s ease-in-out;
    

        &:hover{
            transform: scale(1.05);
        }

        &:hover .card-wrapper{
            transform: scale(0.95);

        }

        .card-wrapper{
            transition: transform 0.35s ease-in-out;
            position: absolute;
            left: 0;
            padding: 0px 43px;
        }

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