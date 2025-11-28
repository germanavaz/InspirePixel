<script setup>
import fotografo from "../assets/fotografo.png"
</script>

<template>
    <section class="banner">
        <section class="texto">
        <h1>Onde a paisagem vira <span>inspiração</span>.</h1>
        <p>Explore paisagens, cores e luzes que inspiram novas histórias através da fotografia.</p>
        </section>
    <img :src="fotografo" alt="">
    </section>
</template>

<style scoped lang="scss">

.banner {
    display: flex;
    font-family: 'Poppins';
    color: #262626;
    width: 85vw;
    height: 85vh;
    align-items: center;
    justify-self: center;

    
    h1 {
        font-size: 3.75rem;
        font-weight: 800;
    }

    span {
        font-size: 5.32rem;
        color: #E1306C;
    }

    p {
        font-weight: 400;
        font-size: 1.5rem;
        width: 50%;
    }
}
</style>