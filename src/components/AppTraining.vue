<script>
export default{
    name: 'AppTraining',
}
</script>

<template> 
<div id="training">
    <div class="container">
        <div class="cards row text-white d-flex flex-row justify-content-between">
            <div class="single-card rounded-2  text-center">
            <div class="mb-3 my-icon">icona</div>
            <p class="mb-0">Team training</p>
            <small >Find a partner</small>
            <p class="my-text">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
            <a href="">Find a partner ></a>
        </div>
        <div class="single-card rounded-2 text-center">
            <div class="mb-3 my-icon">icona</div>
            <p class="mb-0 card-title">Crossifit workout</p>
            <small class="sub-title">Push your limits</small>
            <p class="my-text">Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
            <a href="">Learn about crossfit</a> 
        </div>
        <div class="single-card rounded-2 text-center">
            <div class="mb-3 my-icon">icona</div>
            <p class="mb-0 card-title">Weight loss plan</p>
            <small class="sub-title">Shed those pounds</small>
            <p class="my-text">At laoreet senectus volutpat diam vel sed sed amet pellentesque. Lobortis ut aliquam risus purus. A tellus ut etiam.</p>
            <a href="">Schedule a workout</a> 
        </div>
    </div>
</div> 
</div>
     
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#training{
    background-color: black;
    height: 795px;

    .cards{
        padding-top: 110px;
        padding-bottom: 120px;
        gap:50px;
    }

    .single-card{
        width:calc(100% / 3 - 40px * 3 / 2);
        padding: 80px 60px;
        border: 5px solid $color4;
    }

    .my-text{
        margin-top:50px;
        margin-bottom: 45px;
    }

    .my-icon{
        height: 70px;
        margin-bottom: 35px;
    }
}
</style>