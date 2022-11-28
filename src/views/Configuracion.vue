<template>
    <div>
        <router-link to="/configuracion"><img class="settings" src="../assets/settingsIn.svg" alt=""></router-link>
    </div>
    <div class="contenedorConfig">
        <div class="nYf d-flex align-items-center justify-content-center gap-2 flex-column">
            <img class="fotoPerfil d-flex justify-content-center align-items-center" src="https://media-exp1.licdn.com/dms/image/C4D03AQEVxBZm5y2n6Q/profile-displayphoto-shrink_800_800/0/1661985881943?e=1674691200&v=beta&t=8CERn6k9ldJU8iJfDodAge-8iMI-W-aThR-_sV4cVIw">
            <h2 class="fs-4 fw-light">LaFlor fromUru</h2>
            <p>Cambiar Foto de Perfil</p>
        </div>
        <div class="d-flex flex-column text-center formC"> 
            <form class="d-flex flex-column" action="">
                <label placeholder="Nuevo nombre de usario" class="fs-5 mb-2 text-center">
                    Nombre de Usuario
                </label>
                <input type="text">
                <label class="fs-5 mb-2 text-center">
                    Contraseña
                </label>
                <input type="text">
                <label class="fs-5 mb-2 text-center">Correo Electronico</label>
                <input type="text">
                <label class="fs-5 mb-2 text-center">Genero</label>
                <select name="" id="">
                    <option value="Hombre">Hombre</option>
                    <option value="Mujer">Mujer</option>
                    <option value="Hombre">Otro</option>
                    <option value="Hombre">Prefiero no decirlo</option>
                </select>
                <input id="submit" type="submit" value="Guardar Cambios">
            </form>

        </div>

    </div>
</template>
<style scoped>
.settings{
    width: 1.9rem;
    right: 0 !important;
    top: 0;
    position: absolute;
    margin-top: 1.2rem;
    margin-right: 1rem ;
}
.contenedorConfig{
    margin: auto;
}

.fotoPerfil{
    width: 5.4rem;
    border-radius: 60%;
}
h2{
    color: white;
}
p{
    cursor: pointer;
    color: var(--primario);
}
label{
    color: var(--terciario);
}
input, select{
    border-radius: 10px;
    border: 0;
    background: var(--post);
    color: white;
    width: 14rem;
    height: 2rem;
}
.formC{
    margin: auto;
}
#submit{
    background: var(--primario) !important;
    margin-top: 2rem;
}
</style>