<script>
export default{
    name: 'AppFeatures',
}
</script>

<template> 
<div id="features">
    <div class="container p-0">
        <div class="row row-feat justify-content-between text-white p-0">

            <div class="card-feat position-relative p-0">
                <div class="overlay">
                <img class="img-fluid img-card" src="/images/service6-2x.jpg" alt="">
            </div>
                <div class="my-text-wrap position-absolute bottom-0 left-0">
                    <div class="mb-1">
                    <img class="img-fluid mx-auto separator-w" src="/images/separator-white.png" alt="">
                    <h4>Crossfit workout</h4>
                    <small>Push your limits</small>
                </div>
            </div>
            </div>

            <div class="card-feat position-relative p-0">
                <div class="overlay">
                <img class="img-fluid img-card" src="/images/box1-2x.jpg" alt="">
            </div>
                <div class="my-text-wrap position-absolute bottom-0 left-0">
                    <div class="mb-1">
                    <img class="img-fluid mx-auto separator-w" src="/images/separator-white.png" alt="">
                    <h4>New gym apparel</h4>
                    <small>Look good, feel good</small>
                </div>
            </div>
            </div>

            <div class="card-feat position-relative p-0">
                <div class="overlay">
                <img class="img-fluid img-card" src="/images/box3-2x.jpg" alt="">
                </div>
                <div class="my-text-wrap position-absolute bottom-0 left-0">
                    <div class="mb-1">
                    <img class="img-fluid mx-auto separator-w" src="/images/separator-white.png" alt="">
                    <h4>Team training</h4>
                    <small>Find a partner</small>
                </div>
            </div>
            </div>
                <div class="quote-container col-10 px-4 mx-auto text-white d-flex flex-column align-items justify-content-between">
                    <p class="quote text-center ">"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."   
                    </p>
                    <div class="mb-4 text-center">
                        <img class="img-fluid separator-y" src="/images/separator-yellow.png" alt="">
                    </div>
                        <div class="info-quote text-center">
                            <span><img src="/images/avatar-1-2x.jpg" alt=""></span>
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
    border-radius: 4px;
    border-bottom-right-radius: 40px;
    width: calc(100% / 3 - 25px * 3 / 2);
    overflow: hidden;
    transition: 0.20s ease-in-out;

    .overlay {
    position: relative;
    overflow: hidden;
}

    .overlay::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(180deg, rgba(3, 4, 15, 0) 11%, hsla(240, 8%, 3%, calc(100% - 30%)) 100%); // Filtro gradiente per aumentare il contrasto
}

    &:hover{
            transform: scale(1.05);
        }
        &:hover .my-text-wrap{
            transform: scale(0.95);
        }

        .img-card{
            background-image: linear-gradient(180deg, rgba(3, 4, 15, 0) 11%, hsla(240, 8%, 3%, calc(100% - 30%)) 100%);
        }
    }

.quote-container{
    padding-top: 120px;

.quote{
        font-size:48px;
        line-height: 1.2;
        font-weight: 500;
        padding-left: 25px;
        padding-right:25px;
    }

    .info-quote{
        img{
            width: 60px;
            height: 60px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .name, .location{
            margin: 0 10px;
            font-size: 21px;
        }

        .location{
            opacity: 0.7;
        }
    }

    .separator-y{
        width: 70px;
        margin-top: 20px;
    }
}

.my-text-wrap{
    padding:40px;
    h4{
        font-size: 30px;
    }
    small{
        font-size:24px;
        color:$color6;
        font-weight: 500;
    }
}
}
</style>