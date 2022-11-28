<script setup>
    import Posts from '../components/Posts.vue'
</script>
<template>
    <div>
        <router-link to="/configuracion"><img class="settings" src="../assets/settings.svg" alt=""></router-link>
    </div>
    <div class="perfil">
        <div class="nYf d-flex align-items-center justify-content-center gap-2 flex-wrap">
            <img class="fotoPerfil d-flex justify-content-center align-items-center" src="https://media-exp1.licdn.com/dms/image/C4D03AQEVxBZm5y2n6Q/profile-displayphoto-shrink_800_800/0/1661985881943?e=1674691200&v=beta&t=8CERn6k9ldJU8iJfDodAge-8iMI-W-aThR-_sV4cVIw">
            <h2 class="fs-4 ">LaFlor fromUru</h2>
        </div>
        <div class="posteosPerfil mt-2">
            <Posts class="postPerfilComp"/>
            <Posts class="postPerfilComp"/>
            <Posts class="postPerfilComp"/>
        </div>
    </div>
</template>
<style scoped>
    .perfil{
        margin: auto;
    }
    .nYf{
        background: var(--terciario);
        border-radius: 100%;
    }
    
    .fotoPerfil{
        width: 5.4rem;
        border-radius: 60%;
    }
    h2{
        color: white;
        padding-right: 10px;
        
    }
    .postPerfilComp{
        background: var(--secundario) !important;
    }
    .settings{
        width: 1.9rem;
        right: 0 !important;
        top: 0;
        position: absolute;
        margin-top: 1.2rem;
        margin-right: 1rem ;
    }
</style>