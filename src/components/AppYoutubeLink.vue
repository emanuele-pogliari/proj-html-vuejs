<script>
export default{
    name: 'AppYoutubeLink',
}
</script>

<template> 
<div class="container-fluid p-0" id="youtube">
    <div class="row m-0 p-0">
        
        <div class="col-left p-0 d-flex position-relative ">
            <i class="position-absolute play-btn-big fa-solid fa-play p-5 rounded-circle bg-white"></i>
            <img class="img-fluid" src="/public/images/service15-2x.jpg" alt="">
        </div>
        
        <div class="col-right">
            <h3>Tune up your workouts</h3>
            <p>The best health & fitness advice online</p>
            <div class="d-flex">
                <img class="unamed" src="/public/images/unnamed.jpg" alt="">
                <div class="d-flex flex-column ">
                    <small>ThemeFusion</small>
                    <div class="youtube-button d-flex">
                        <div class="red"><i class="me-1 fa-brands fa-youtube"></i>YouTube</div>
                        <div class="count">999+</div>
                    </div>
                </div>
            </div>
            <p class="text-desc">Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
            <button class="btn my-btn rounded-pill"><i class="me-1 fa-brands fa-youtube"></i>Visit my Youtube channel</button>
        </div>
    </div>
</div> 
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#youtube{
    max-width: 1920px;

    h3{
        font-size: 28px;
        color:$color4;
    }

    p{
        font-size: 62px;
        font-weight: 500;
    }

    .text-desc{
        font-size: 23px;
        color:#98939F;
        font-weight: 400;
    }

    .col-left{
        width:50%;
        height:778px;
        margin-top: -60px;

        .play-btn-big{
            top: 42%;
            left:44%;
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

    .col-right{
        width:50%;
        padding: 135px;

        .my-btn{
            background-color: red;
        }

        .unamed{
        width:41px;
        height: 100%;
        object-fit: cover;
        margin-right:15px;
    }
        
    
    .youtube-button{
        border: 1px solid rgba(223, 220, 220, 0.767);
        border-radius: 1px;
        display: flex;
        align-items: center;
        font-size: 10px;
        margin-bottom: 30px;
        
        
        .red{
            background-color: #E62117;
            color:white;
            vertical-align: middle;
            padding: 2px 10px;
        }
        .count{
            vertical-align: middle;
            padding: 2px 5px;
            color:#98939F;
        }

    }

  

    }

   

    


}

</style>