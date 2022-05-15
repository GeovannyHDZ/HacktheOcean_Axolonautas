<script>
export default {
    
}
</script>

<template>
    <div class="about_us"><!--Contenedor-->
        <div class="images"> <!--Imagen-->
                <img src="../assets/Logos/photos.png" alt="">
        </div>
        <div class="info"> <!--Información que contiene Texto, imagenes y botones-->
            <div class="texto"> <!--Texto-->
                <h3>Acerca De Nosotros</h3>
                <p>Somos una asociación dedicada a la divulgación del impacto que tienen las empresas refresqueras al explotar los recursos naturales para la producción de bienes. <br><br>
                    Por el crecimiento de la población y su estilo de consumo se ha incrementado la contaminación, que destruye el océano nacional mexicano.</p>
            </div>
            <div class="donar-btn"> <!--Boton-->
                <button>Donar</button>
            </div>
        </div>
    </div>
</template>

<style>
about_us{
    height: 400px;
    width: 100%;
    display:grid;
    grid-template-columns: 0.5fr 0.5fr;
    margin: auto;
    overflow: hidden;
    box-sizing: border-box;
    background-image:url("../assets/Logos/coran.png");
    background-position: 50% 20%;
    
}
.about_us .images{
    width: 100%;
    display: flex;
    align-items: center;
    padding-left: 10%;
}
.about_us .images img{
    height: 400px;
}

.info{
    width: 70%;
    padding: 30px 0 0 50px;
}
.texto{
    width: 100%;
}
.texto h3{
    color: white;
    font-size: 23px;
}
.texto p{
    color: white;
    font-size: 18px;
}
.donar-btn{
    padding-top: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.donar-btn button{
    height: 40px;
    width: 120px;
    border: none;
    border-radius: 16px;
    font-weight: bold;
    font-size: 16px;
}
.donar-btn button:hover{
    background-color: #f4bcb6;
    transition: 0.6s;
    color: white;
}
</style>