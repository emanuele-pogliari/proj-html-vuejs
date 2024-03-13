<script>
export default{
    name: 'AppVideos',
}
</script>

<template> 
<div class="container-fluid" id="videos">
    <div class="container">
    <div class="row">
        <div class="col d-flex px-0 pb-4 justify-content-between align-items-center ">
            <h3>Featured Playlist</h3>
            <a class="px-4 py-1 text-black">View all videos <i class="ms-2 fa-solid fa-angle-right"></i></a>
        </div>
        <div class="video-container p-0 justify-content-between ">

            <div class="single-video">
                <div class="img-card position-relative">
                    <i class="play-btn-small fa-solid fa-play position-absolute"></i>
                    <img class="img-fluid" src="/public/images/video2-2x.jpg" alt="">
                </div>

                <div class="text-box text-center d-flex flex-column mt-4">
                    <p class="text fs-4">Thighs & glute workout</p>
                    <small class="sub-text fs-5">Increase your mobility</small>
                </div>

            </div>

            <div class="single-video">
                <div class="img-card position-relative">
                    <i class="play-btn-small fa-solid fa-play position-absolute"></i>
                    <img class="img-fluid" src="/public/images/video7-2x.jpg" alt="">
                </div>

                <div class="text-box text-center d-flex flex-column mt-4">
                    <p class="text fs-4">Lift, firm & perk up</p>
                    <small class="sub-text fs-5">Feel young again</small>
                </div>
            </div>

            <div class="single-video ">
                <div class="img-card position-relative">
                    <i class="play-btn-small fa-solid fa-play position-absolute"></i>
                    <img class="img-fluid" src="/public/images/video9-2x.jpg" alt="">
                </div>
                
                <div class="text-box text-center d-flex flex-column mt-4">
                    <p class="text fs-4">Slim & trim your waist</p>
                    <small class="sub-text fs-5">Increase your mobility</small>
                </div>
            </div>

        </div>
    </div>
</div>
</div> 
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#videos{
    padding: 110px 130px;

    .video-container{
        display: flex;
        flex-direction: row;
        gap: 20px;
   
    .single-video{
        width: calc(100% / 3 - 20px * 3 / 2);
        
        img{
            border-radius: 4px;
            border-bottom-right-radius: 40px;
            overflow: hidden;
        }
        .text{
        margin-bottom:0;
    }
    .sub-text{
        color: $color4;

    }
    }

    .play-btn-small{
        top:50%;
        left: 50%;
        transform: translate(-50%,-50%);
    }

    

    }
}
</style>