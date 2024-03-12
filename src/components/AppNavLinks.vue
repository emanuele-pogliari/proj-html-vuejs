<script>
export default{
    name: 'AppNavlinks',

    props:{
        links: String,
    }
}
</script>

<template>
    <li class="nav-item">
      <a class="nav-link" href="#">{{links}}</a>
    </li>
       
</template>

<style></style>