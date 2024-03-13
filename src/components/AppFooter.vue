<script>
import {store} from '../store.js';
import AppFooterLinks from './AppFooterLinks.vue';

export default{
    name: 'AppFooter',
    
    components:{
        AppFooterLinks,
    },

    data() {
        return {
            store,
        }
    },
}
</script>

<template> 
<footer id="footer">
    
    <div class="footer-top">
        <div class="container text-center d-flex justify-content-center">
        <div class="single-col p-0">
            <img src="/public/images/logo.png" alt="">
            <p class="text-logo">Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pallentesque consectetur amet purus ultrices mauris.</p>
            <div class="socials">
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
                <AppFooterLinks v-for="flink in store.footerLinks" :Flinks="flink"></AppFooterLinks>
            </ul>
        </div>
        <div class="contacts single-col p-0">
            <h5 class="pb-3 text-uppercase">Contact informations</h5>
            <p class="address">4746 Tipple Road Michigan 48449</p>
            <p class="phone">Mobile: 1.800.000.0000</p>
            <p>Email: info@your-company.com</p>
        </div>
    </div>
    
</div>
<div class="footer-bottom text-center">
        <p class="text-bottom">&copy Copyright 2012 - 2020 | Avada Website Builder by <span>ThemeFusion </span>| All Rights Reserved | Powered by <span>WordPress</span></p>
    </div>
</footer> 
</template>

<style scoped lang="scss">
@use '/src/styles/variables.scss' as *;
#footer{
    color:white;
    background-color:$color1;
    .footer-top{
        padding-top: 150px;
        padding-bottom: 110px;
    
        h5{
            font-size: 23px;
            margin-bottom: 30px;
        }
        .contacts{
            font-size: 20px;
        }
        img{
            margin-bottom: 15px;
        }

        .text-logo{
            margin-bottom: 50px;
            font-size: 20px;
            color: #FFFFFFC7
        }

        .socials{
            display: flex;
            justify-content: center;
            gap:20px;
            color:$color5;
        }

    

    .single-col{
        width: calc(100% / 3);
    }
    .address{
        color:$color3;
    }

    .phone{
        margin-bottom: 0;
    }
}

.footer-bottom{
    border-top: 1px solid grey ;
    padding: 20px;
    .text-bottom{
        color:$color3;
        margin-top: 16px;
    span{
        color:white;
    }
    }
    

}

}
</style>