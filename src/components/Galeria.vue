<template>
  <div class="galeriaFotos">
    <h1 class="titulo-galeria">Halloween memories</h1>
    <ul class="navegacao-fotos">
      <li class="fotoUm">
        <img
          src="@/assets/4305e376ef71596a5a8d8701cc6c01bd.png"
          alt=" Um homem e duas mulheres com fantasia"
        />
      </li>
      <li class="fotoDois">
        <img
          src="@/assets/7e0a2df8f6a053f3274d0796dff1af32.png"
          alt="Um homem e duas mulheres com fantasia"
        />
      </li>
      <li class="fotoTres">
        <img
          src="@/assets/98b62d68c47a25c79ece1960ac935ef2.png"
          alt="fantasia halloween"
        />
      </li>
      <li class="fotoQuatro">
        <img
          src="@/assets/a2e2e7c9273e8aa9f99eb51016e76748.png"
          alt="Um homem e quatro mulheres com fantasia"
        />
      </li>
      <li class="fotoCinco">
        <img src="@/assets/a8facd22fbe0ace329d6a0e52bbac822.png" alt="" />
      </li>
      <li class="fotoSeis">
        <img
          src="@/assets/b3946557f1b2b5f8b84f6efff6c7ccf6.png"
          alt="Um homem e duas mulheres conversando, Utilizando fantasia "
        />
      </li>
      <li class="fotoSete">
        <img src="@/assets/e8be9da0f14481265e829dd5e20e2e9d.png" alt="" />
      </li>
      <li class="fotoOito">
        <img
          src="@/assets/f5ee8f61c1a224b3e3fe33bf0fc00b98.png"
          alt="Um homem fansiado"
        />
      </li>
      <li class="fotoNove">
        <img src="@/assets/f5ee8f61c1a224b3e3fe33bf0fc00b98.png" alt="" />
      </li>
      <li class="fotoDez">
        <img src="@/assets/fcdbf175ebc041f1f93b8f948ab2fea1.png" alt="" />
      </li>
    </ul>
  </div>
</template>



<script>
export default {
    name:"GaleriaHalloween"
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