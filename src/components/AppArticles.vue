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
            <h3>Latest articles</h3>
            <a class="px-4 py-2 text-black">Read all articles<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>
        <div class="article-container p-0 justify-content-between ">
            <div class="single-article position-relative">
                <img class="img-fluid" src="/images/blog4-2x.jpg" alt="">
                <div class="text-box d-flex flex-column mt-4">
                    <p class="article-title mb-1 fs-4">The best protein shake</p>
                    <small class="sub-text fs-5">Published On: November 26th, 2019 | 2 Comments</small>
                </div>
            </div>
            <div class="single-article position-relative">
                <div class="img-container">
                    <img class="img-fluid" src="/images/blog1-2x.jpg" alt="">
                </div>
                <div class="text-box d-flex flex-column mt-4">
                    <p class="article-title mb-1 fs-4">Ultimate cardio workout</p>
                    <small class="sub-text fs-5">Published On: November 26th, 2019 | 0 Comments</small>
                </div>
            </div>
            <div class="single-article position-relative">
                <img class="img-fluid" src="/images/blog3-2x.jpg" alt="">
                <div class="text-box d-flex flex-column mt-4">
                    <p class="article-title mb-1 fs-4">New juices available now</p>
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
        gap: 25px;
   
    .single-article{
        width: calc(100% / 3 - 25px * 3 / 2);

    .img-container {
        position: relative;            
        overflow: hidden;
    }


        .article-title{
            font-weight: 500;
        }
    }

    }
}
</style>