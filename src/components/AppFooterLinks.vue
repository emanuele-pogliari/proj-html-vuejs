<script>
export default{
    name: 'AppFooterLinks',

    props:{
        Flinks: Array,
    }
}
</script>

<template>
    <li class="nav-item">
      <a class="nav-link" href="#">{{Flinks}}</a>
    </li>
       
</template>