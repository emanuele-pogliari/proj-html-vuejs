<script>
export default{
    name: 'AppArticles',
}
</script>

<template> 
<div class="container-fluid" id="articles">
    <div class="container">
    <div class="row pt-5">
        <div class="col d-flex px-0 pb-4 justify-content-between align-items-center ">
            <h3>Featured Playlist</h3>
            <a class="px-3 py-1 text-black">View all videos ></a>
        </div>
        <div class="video-container p-0 justify-content-between ">
            <div class="single-video position-relative">
                <img class="img-fluid" src="/public/images/video2-2x.jpg" alt="">
                <div class="text-box text-center d-flex flex-column mt-4">
                    <p class="mb-2 fs-4">Thighs & glute workout</p>
                    <small class="sub-text fs-5">Increase your mobility</small>
                </div>
            </div>
            <div class="single-video position-relative">
                <img class="img-fluid" src="/public/images/video7-2x.jpg" alt="">
                <div class="text-box text-center d-flex flex-column mt-4">
                    <p class="mb-2 fs-4">Lift, firm & perk up</p>
                    <small class="sub-text fs-5">Feel young again</small>
                </div>
            </div>
            <div class="single-video position-relative">
                <i class="play-btn fa-solid fa-play p-3 rounded-circle bg-white position-absolute "></i>
                <img class="img-fluid" src="/public/images/video9-2x.jpg" alt="">
                <div class="text-box text-center d-flex flex-column mt-4">
                    <p class="mb-2 fs-4">Slim & trim your waist</p>
                    <small class="sub-text fs-5">Increase your mobility</small>
                </div>
            </div>
        </div>
    </div>
</div>
</div> 
</template>

<style scoped lang="scss">
#articles{
    padding: 110px 130px;

    .video-container{
        display: flex;
        flex-direction: row;
        gap: 20px;
   
    .single-video{
        width: calc(100% / 3 - 20px * 3 / 2);
        img{
        border-radius: 4px;
        overflow: hidden;
        }
    }

    }
}
</style>