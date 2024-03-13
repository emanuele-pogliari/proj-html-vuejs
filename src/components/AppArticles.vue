<script>
export default{
    name: 'AppArticles',
}
</script>

<template> 
<div class="container-fluid" id="articles">
    <div class="container">
    <div class="row">
        <div class="col d-flex px-0 pb-4 justify-content-between align-items-center ">
            <h3>Featured Playlist</h3>
            <a class="px-3 py-1 text-black">Read all news ></a>
        </div>
        <div class="article-container p-0 justify-content-between ">
            <div class="single-article position-relative">
                <img class="img-fluid" src="/images/video2-2x.jpg" alt="">
                <div class="text-box d-flex flex-column mt-4">
                    <p class="mb-2 fs-4">The best protein shake</p>
                    <small class="sub-text fs-5">Published On: November 26th, 2019 | 2 Comments</small>
                </div>
            </div>
            <div class="single-article position-relative">
                <img class="img-fluid" src="/images/video7-2x.jpg" alt="">
                <div class="text-box d-flex flex-column mt-4">
                    <p class="mb-2 fs-4">Ultimate cardio workout</p>
                    <small class="sub-text fs-5">Published On: November 26th, 2019 | 0 Comments</small>
                </div>
            </div>
            <div class="single-article position-relative">
                <i class="play-btn fa-solid fa-play p-3 rounded-circle bg-white position-absolute "></i>
                <img class="img-fluid" src="/images/video9-2x.jpg" alt="">
                <div class="text-box d-flex flex-column mt-4">
                    <p class="mb-2 fs-4">New juices available now</p>
                    <small class="sub-text fs-5">Published On: November 26th, 2019 | 0 Comments</small>
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

    .article-container{
        display: flex;
        flex-direction: row;
        gap: 30px;
   
    .single-article{
        width: calc(100% / 3 - 30px * 3 / 2);
        img{
        border-radius: 4px;
        overflow: hidden;
        }

    }

    }
}
</style>