<script>
export default{
    name: 'AppFeatures',
}
</script>

<template> 
<div id="features">
    <div class="container">
        <div class="row row-feat justify-content-between text-white gap-3 m-0 p-0">

            <div class="col-3 card-feat position-relative m-0 p-0">
                <img class="img-fluid" src="/public/images/service6-2x.jpg" alt="">
                <div class="position-absolute bottom-0 left-0">
                    <span>chevrons</span><span>chevrons</span><span>chevrons</span>
                    <h4>Crossfit Workout</h4>
                    <small>Push your limits</small>
                </div>
            </div>

            <div class="col-3 card-feat position-relative">
                <img class="img-fluid" src="/public/images/box1-2x.jpg" alt="">
                <div class="position-absolute bottom-0 left-0">
                    <span>chevrons</span><span>chevrons</span><span>chevrons</span>
                    <h4>Crossfit Workout</h4>
                    <small>Push your limits</small>
                </div>
            </div>

            <div class="col-3 card-feat position-relative m-0 p-0">
                <img class="img-fluid" src="/public/images/box3-2x.jpg" alt="">
                <div class="position-absolute bottom-0 left-0">
                    <span>chevrons</span><span>chevrons</span><span>chevrons</span>
                    <h4>Crossfit Workout</h4>
                    <small>Push your limits</small>
                </div>
            </div>
                <div class="quote-container col-10 px-4 mx-auto text-white d-flex flex-column align-items justify-content-between">
                    <p class="quote text-center ">"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."   
                    </p>
                        <div class="">
                            
                        </div>
                        <div class="info-quote text-center">
                            <span><img src="/public/images/avatar-1-2x.jpg" alt=""></span>
                            <span class="name">Brad Johnson</span>
                            <span class="location">Las Vegas</span>
                        </div>
                    </div>
                </div>
        </div>
    </div>   
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#features{
    background: linear-gradient(150deg, hsl(234, 100%,calc(63% - 20%), 100%) 0%, hsla(357, 100%,calc(63% - 20%), 100%) 100%);
    padding-bottom: 100px;
    .row-feat{
        transform: translateY(-80px);
    }

    .card-feat{
    width: calc(100% / 3 - 30px * 3 / 2);
    overflow: hidden;

        img{
            height: 100%;
            border-radius: 4px;
            border-bottom-right-radius: 40px;
        }
    }

.quote-container{
    padding-top: 100px;
}

.quote{
        font-size:48px;
        line-height: 1.2;
    }

    .info-quote{
        img{
            width: 60px;
            height: 60px;
            border-radius: 50%;
        }
        .name, .location{
            padding: 0 10px;
            font-size: 21px;
        }
    }
}
</style>