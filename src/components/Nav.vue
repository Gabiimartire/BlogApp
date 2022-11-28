<script setup>
    import { RouterLink, RouterView } from "vue-router";
</script>
<template>
    <label for="btn-nav" class="btn-nav">☰</label>
    <input type="checkbox" id="btn-nav">
    
    <nav>
        <ul class="navigation">
            <RouterLink to="/"><h2 class="navH2 my-2">BlogApp</h2></RouterLink>
            <li><a href="">Sobre Nosotros</a></li>
            <li><RouterLink to="/contact">Contactanos</RouterLink></li>
            <li><a href="">Reglas y Politicas</a></li>
        </ul>
    </nav>
    <RouterView />
</template>