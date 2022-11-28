<script setup>
    import Comment from './icons/CommentB.vue';
    import Favourite from './icons/FavouriteB.vue';
    import Share from './icons/ShareB.vue';
</script>
<template>
    <div class="postBlogApp mx-4">
        <div class="nAiUser d-flex pt-2 px-3">
            <img
            class="imagenPerfil"
            src="https://media-exp1.licdn.com/dms/image/C4D03AQEVxBZm5y2n6Q/profile-displayphoto-shrink_800_800/0/1661985881943?e=1674691200&v=beta&t=8CERn6k9ldJU8iJfDodAge-8iMI-W-aThR-_sV4cVIw"
            alt="">
            <h3 class="nUsuario text-white fw-normal fs-5">LaFlor fromUru</h3>
        </div>
            <p class="post text-light p-2">¡Oy! Me Enojé</p>
        <div class="botones-interaccion mx-2 my-3">
            <Favourite class="botones" />
            <Comment class="botoness" />
            <Share class="botoness" />
        </div>
    </div>
</template>
<style scoped>
    .nAiUser{
        display: flex;
    }
    .nUsuario{
        margin-top: .3rem;
    }
    .postBlogApp{
        margin: auto !important;
        width: 15rem;
        min-height: 2rem;
        border-radius: 2rem;
        background: #212D40;
        margin-bottom: 1rem !important;
        border: 1px solid rgb(255, 255, 255);
    }
    .post{
        border-bottom: 1px solid #D66853;
    }
    .botones-interaccion{
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .botones{
        margin: auto;
        width: 1.2rem;
        height: 1.2rem;
    }
    .botoness{
        margin: auto;
        width: 1rem;
        height: 1rem;
    }
</style>