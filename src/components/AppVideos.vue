<script>
export default{
    name: 'AppVideos',
}
</script>

<template> 
<div class="container" id="videos">
    <div class="row">
        <div class="col d-flex justify-content-between">
            <div>Featured Playlist</div>
            <div>View all videos</div>
        </div>
        <div class="video-container d-flex">
            <div class="col-4 px-4 single-video">
                <img class="img-fluid" src="/public/images/video2-2x.jpg" alt="">
                <div>
                    <p>Thighs & glute workout</p>
                    <small>Increase your mobility</small>
                </div>
            </div>
            <div class="col-4 px-4 single-video">
                <img class="img-fluid" src="/public/images/video7-2x.jpg" alt="">
                <div>
                    <p>Lift, firm & perk up</p>
                    <small>Feel young again</small>
                </div>
            </div>
            <div class="col-4 px-4 single-video">
                <img class="img-fluid" src="/public/images/video9-2x.jpg" alt="">
                <div>
                    <p>Slim & trim your waist</p>
                    <small>Increase your mobility</small>
                </div>
            </div>
        </div>
    </div>

</div> 
     
</template>

<style scoped lang="scss">
#videos{
    height: 705px;

    .single-video{
        img{
        border-radius: 4px;
        border-bottom-right-radius: 40px;
        overflow: hidden;
        }
    }
}
</style>