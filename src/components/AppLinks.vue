<script>
export default{
    name: 'AppLinks',
}
</script>

<template> 
<div class="container" id="links">

    <div class="row justify-content-center ">
        <div class="single-link">
            <div class="img-box">
                <img src="/public/images/sponsor-1-2x.png" alt="">
            </div>
            <p>Tristique aliquam in nullam habitasse nunc, amet vel consectetur. Nulla in suspendisse dolor, aliquet.</p>
            <a href="">Visit Yoga Studio</a>
            
        </div>
        <div class="single-link">
            <div class="img-box">
                <img src="/public/images/sponsor-2-2x.png" alt="">
            </div>
            <p>Feugiat etiam dui mauris pharetra mauris sed pharetra. Convallis sapien ornare cras faucibus nulla porta dui a.</p>
            <a href="">Join Fitness Center</a>
        </div>
        <div class="single-link">
            <div class="img-box">
            <img src="/public/images/sponsor-3-2x.png" alt="">
        </div>
            <p>Nisl at quam adipiscing montes, nec, adipiscing commodo aliquam tincidunt. Ligula in habitant et sagittis imperdiet.</p>
            <a href="">Join Fitness Center</a>
        </div>
        <div class="single-link">
            <div class="img-box">
            <img src="/public/images/sponsor-4-2x.png" alt="">
        </div>
            <p>Proin in viverra maecenas et mattis ut nibh enim. Gravida ultricies mi porta lacus. Et posuere velit sed nec eleifend.</p>
            <a href="">Visit Power Gym</a>
        </div>
    </div>

</div> 
     
</template>

<style scoped lang="scss">
#links{
}

.single-link{
    width: calc(100% / 4);
}
</style>