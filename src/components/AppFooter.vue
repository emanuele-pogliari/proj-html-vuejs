<script>
export default{
    name: 'AppFooter',
}
</script>

<template> 
<footer id="footer">
    <div class="container text-center">
    <div class="footer-top d-flex justify-content-center ">
        <div class="single-col p-0">
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
        <div class="single-col p-0">
            <h5 class="text-uppercase">Recent Posts</h5>
            <ul class="list-unstyled">
                <li><a href="">> The best protein shake</a></li>
                <li><a href="">> Ultimate cardio workout</a></li>
                <li><a href="">> New juices available now</a></li>
                <li><a href="">> Tips to find training partners</a></li>
                <li><a href="">> 20 best healthy recipes</a></li>
            </ul>
        </div>
        <div class="contacts single-col p-0">
            <h5 class="pb-3 text-uppercase">Contact informations</h5>
            <p>4746 Tipple Road Michigan 48449</p>
            <p>Mobile: 1.800.000.0000</p>
            <p>Email: info@your-company.com</p>
        </div>
    </div>
    <div class="footer-bottom">
        <p>C Copyright 2012 - 2020 | Avada Website Builder by ThemeFusion|All Rights Reserved|Powered by WordPress</p>
    </div>
</div>
</footer> 
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#footer{
    color:white;
    background-color:$color1;
    height: 665px;
    .footer-top{
        padding-top: 120px;
        padding-bottom: 110px;
    
        h5{
            font-size: 23px;
            margin-bottom: 30px;
        }
        .contacts{
            font-size: 20px;
        }

    }


    li{
        padding-top: 10px;
        padding-bottom: 10px;

        a{
            font-size: 20px;
        }
    }

    .single-col{
        width: calc(100% / 3);
    }
}
</style>