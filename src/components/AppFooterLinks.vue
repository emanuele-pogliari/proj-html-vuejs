<script>
export default{
    name: 'AppFooterLinks',

    props:{
        Flinks: String,
    }
}
</script>

<template>
    <li class="nav-item">
      <a class="nav-link" href="#"><i class="me-1 fa-solid fa-angle-right"></i>{{Flinks}}</a>
    </li>
       
</template>


<style scoped lang="scss">
li{
        padding-top: 10px;
        padding-bottom: 10px;

        a{
            font-size: 20px;
        }
    }
</style>