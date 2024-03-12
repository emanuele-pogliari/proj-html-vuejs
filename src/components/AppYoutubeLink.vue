<script>
export default{
    name: 'AppYoutubeLink',
}
</script>

<template> 
<div class="container-fluid p-0" id="youtube">
    <div class="row h-100 m-0 p-0">
        <div class="col-left p-0">
            <img class="img-fluid" src="/public/images/service15-2x.jpg" alt="">
        </div>
        <div class="col-right">
            <h3>Tune up your workouts</h3>
            <p>The best health & fitness advice online</p>
            <div class="d-flex">
                <img class="unamed" src="/public/images/unnamed.jpg" alt="">
                <div class="d-flex flex-column ">
                    <small>ThemeFusion</small>
                    <div class="d-flex">
                        <div>Youtube</div>
                        <div>999+</div>
                    </div>
                </div>
            </div>
            <p class="text-desc">Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
            <button class="btn btn-danger rounded-pill"><i class="fa-brands fa-youtube"></i>Visit my Youtube channel</button>
        </div>
    </div>
</div> 
     
</template>

<style scoped lang="scss">
#youtube{
    max-width: 1920px;

    h3{
        font-size: 28px;
    }

    p{
        font-size: 62px;
        font-weight: 500;
    }

    .text-desc{
        font-size: 23px;
        color:#98939F;
    }

    .col-left{
        width:50%;
        height:100%;
        transform: translateY(-60px);
    }

    .col-right{
        width:50%;
        padding: 135px;
    }


    img{
        width: 100%;
        height: 100%;
        border-radius: 4px;
        border-bottom-right-radius: 40px;
        object-fit: cover;
        overflow: hidden;
    }

    .unamed{
        width:41px
    }
}

</style>