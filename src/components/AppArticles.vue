<script>
export default{
    name: 'AppArticles',
}
</script>

<template> 
<div class="container" id="articles">
    <div class="row">
        <div class="col d-flex justify-content-between">
            <div>Latest Articles</div>
            <div>Read all articles</div>
        </div>
        <div class="article-container d-flex">
            <div class="col-4 px-4 single-article">
                <img class="img-fluid" src="/public/images/blog4-2x.jpg" alt="">
                <div>
                    <p>The best protein shake</p>
                    <small>Published on: November 26th, 2019 | 2 comments</small>
                </div>
            </div>
            <div class="col-4 px-4 single-article">
                <img class="img-fluid" src="/public/images/blog1-2x.jpg" alt="">
                <div>
                    <p>Ultimate cardio workout</p>
                    <small>Published on: November 26th, 2019 | 0 comments</small>
                </div>
            </div>
            <div class="col-4 px-4 single-article">
                <img class="img-fluid" src="/public/images/blog3-2x.jpg" alt="">
                <div>
                    <p>New juices available now</p>
                    <small>Published on: November 26th, 2019 | 0 comments</small>
                </div>
            </div>
        </div>
    </div>

</div> 
</template>

<style lang="scss">
#articles{
    height: 695px;

    .single-article{
        img{
        border-radius: 4px;
        }
    }
}
</style>