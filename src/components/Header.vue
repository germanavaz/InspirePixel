<script setup>
import { Icon } from "@iconify/vue"
import logo from "../assets/logo.png"
</script>

<template>
    <header class="header">
        <img :src="logo" alt="">
        <nav>
           <li><a href=""> <Icon class="search-icon icon" icon="material-symbols:search"/> </a></li>
           <li><a href="">Início</a></li>
           <li><a href="">Galeria</a></li>
           <li><a href="">Favoritos</a></li>
           <li><a href=""><Icon class="person-icon icon" icon="material-symbols:person-outline"/></a></li>
        </nav>
    </header>
</template>

<style scoped lang="scss">

header {
    display:flex;
    justify-content: space-between;
    padding: 10px 30px;
}

img {
    width: 50px;
    height: 49px;
}

nav {
    display: flex;
    width: 500px;
    justify-content: space-between;
    align-items: center;
    

    li {
       list-style-type: none; 
       
    }

    a {
        text-decoration: none;
        color: #262626;
        font-size: 1.5rem;
        font-weight: 400;
        font-family: 'Poppins';

        .icon {
            width: 24px;
        }

        .person-icon {
            color: #E1306c !important;
            }
    }
}




</style>