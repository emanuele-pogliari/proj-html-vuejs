<script>
export default{
    name: 'AppFooter',
}
</script>

<template> 
<footer class="container" id="footer">
    <div class="row footer-top">
        <div class="col-4">
            <img src="/public/images/logo.png" alt="">
            <p>Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pallentesque consectetur amet purus ultrices mauris.</p>
            <div>
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-x-twitter"></i>
                <i class="fa-brands fa-square-instagram"></i>
                <i class="fa-brands fa-youtube"></i>
                <i class="fa-brands fa-linkedin-in"></i>
            </div>
        </div>
        <div class="col-4">
            <h5>Recent Posts</h5>
            <ul>
                <li>The best protein shake</li>
                <li>Ultimate cardio workout</li>
                <li>New juices available now</li>
                <li>Tips to find training partners</li>
                <li>20 best healthy recipes</li>
            </ul>
        </div>
        <div class="col-4">
            <h5>Contact informations</h5>
            <p>4746 Tipple Road Michigan 48449</p>
            <p>Mobile: 1.800.000.0000</p>
            <p>Email: info@your-company.com</p>
        </div>
    </div>
    <div class="footer-bottom">
        <p>C Copyright 2012 - 2020 | Avada Website Builder by ThemeFusion|All Rights Reserved|Powered by WordPress</p>
    </div>
</footer> 
     
</template>

<style lang="scss">
#footer{
    background-color:greenyellow;
    height: 665px;
}
</style>