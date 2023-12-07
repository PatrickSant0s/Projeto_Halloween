<template>
  <div class="galeriaFotos">
    <h1 class="titulo-galeria">Halloween memories</h1>
    <ul class="navegacao-fotos">               
                                      <!-- key = dizer para o V-for que cada arquivo é diferente-->
      <li class="fotos" v-for="foto in images " :key="foto.src">
                      <!-- require serve para acessar o modulo -->
       <img  :src="require(`@/assets/${foto.src}.png`)" :alt="foto.alt" >
      </li>
    </ul>
  </div>
  
</template>



<script>

import {images} from "@/utils/galeriaFotos"



export default {
    name:"GaleriaHalloween",


    //importa função de outro arquivo.
computed: {


  images(){
    console.log(images)
    return images
  }
} 

    

};

</script>




<style scoped>
.titulo-galeria {
    padding: 100px 0 40px 0;
    text-align: center;
    font-family: var(--fonte-principal);
    font-size: 55px;
    font-weight: 40;
    text-transform: uppercase;
    color: var(--color-principal);
    font-style: normal;
}

.galeriaFotos img {
    width: 243px;
    height: 242px;
    border-radius: 16px;

}
.navegacao-fotos {
    display: grid;
    grid-template-columns: repeat(5, 250px);
    grid-template-rows: 2;
    justify-content: space-between;
    gap: 3rem;
    column-gap: rem;



}


</style>