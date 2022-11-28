<script setup>  
import Comment from './icons/CommentB.vue';
import Favourite from './icons/FavouriteB.vue';
import Share from './icons/ShareB.vue';

</script>

<template>

    <div class="d-flex align-items-center justify-content-center">
      <h2 class="border-bottom text-center text-white mt-5 pb-2">
        Bienvenidos a <span class="span1">BlogApp</span>
      </h2>
    </div>
    <div class="justify-content-center m-auto" style="width: 20rem">
      <p class="text-white fs-4 text-center p-presentacion border-bottom pb-3">
        <span class="span1">BlogApp</span> permite que los grupos de amigos, familiares y
        compañeros de trabajo se comuniquen y estén en contacto a través de mensajes rápidos
        y frecuentes. Las personas publican lo que piensan, que pueden contener fotos,
        videos, enlaces y texto.
      </p>
    </div>
    <div class="d-flex justify-content-center">
      <h3 class="text-white fw- fs-5 text-center border-bottom pb-2">
        Post con mas favoritos
      </h3>
    </div>

    <!-- post -->
    <div class="postBlogApp mx-4">
      <div class="nAiUser d-flex pt-2 px-3">
        <img
          class="imagenPerfil"
          src="https://elcomercio.pe/resizer/pfVziOV4X8Vu9nwknDc-oNItlB8=/1200x900/smart/filters:format(jpeg):quality(75)/cloudfront-us-east-1.images.arcpublishing.com/elcomercio/6Y2EDIISGFGVFANEVDCR5LCG34.jpg"
          alt=""
        />
        <h3 class="nUsuario text-white fw-normal fs-5">Goku LeGana</h3>
      </div>
      <p class="post text-light p-2">
        Alguien tiene el video donde me transformo en ssj3? Se lo quiero mostrar a vegeta
      </p>
      <div class="botones-interaccion my-3">
        <Favourite class="botones" />
        <Comment class="botones"/>
        <Share class="botones"/>
      </div>
    </div>
    <!-- post -->
    <div class="postBlogApp mx-4">
      <div class="nAiUser d-flex pt-2 px-3">
        <img
          class="imagenPerfil"
          src="data:image/jpeg;base64,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"
          alt="">
          <h3 class="nUsuario text-white fw-normal fs-5">Chamber</h3>
        </div>
        <p class="post text-light p-2">You Want To Play Let's Play</p>
        <div class="botones-interaccion mx-2 my-3">
        <Favourite class="botones" />
        <Comment class="botones" />
        <Share class="botones" />
      </div>
    </div>
    <div class="postBlogApp mx-4">
      <div class="nAiUser d-flex pt-2 px-3">
        <img
          class="imagenPerfil"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRn-W2vKcrvyQNaEaQFnkq-ErID6lj0QxBjyQ&usqp=CAU"
          alt="">
          <h3 class="nUsuario text-white fw-normal fs-5">Neon</h3>
        </div>
        <p class="post text-light p-2">¡Oy! Me Enojé</p>
        <div class="botones-interaccion mx-2 my-3">
        <Favourite class="botones" />
        <Comment class="botones" />
        <Share class="botones" />
      </div>
    </div>

</template>

<style scoped>
.p-presentacion {
  line-height: 1.4rem;
}
.span1 {
  font-weight: bold;
  color: #d66853;
}
</style>
