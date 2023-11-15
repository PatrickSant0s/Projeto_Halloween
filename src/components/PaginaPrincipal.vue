<template>
  <div class="principal" id="principalOne">
    <div class="hero">
      <div class="container-calendario">
        <img src="@/assets/calendar.png" alt="" class="imagem_calendario" />
        <p class="data">31 Octobr 2023</p>
      </div>

      <h1 class="titulo-principal">It's Halloween Party O'Clock!</h1>
    </div>
  </div>
</template>

<script>
export default {
    name:"PaginaPrincipal"
};
</script>


<style scoped>
#principalOne {
  background-image: url(@/assets/imagemDeFundo.png);
  background-position: center;
  background-size: cover;
  width: 100%;
  height: 100vh;
  background: rgba(0, 0, 0, 0), rgba(0, 0, 21, 1);
  border: none;
}

div.container-calendario {
  display: flex;
  align-items: center;
  gap: 15px;
  font-family: var(--fonte-secundaria);
  text-transform: uppercase;
  color: #fff;
  font-weight: 400;
  font-size: 24px;
  font-style: normal;
  padding-right: 50px;
}
.hero {
  padding-top: 40px;
  gap: 10px;
  display: grid;
  color: #fff;
  flex-direction: column;
  justify-items: center;
  align-items: center;
}
.titulo-principal {
  font-family: var(--fonte-principal);
  color: var(--color-principal);
  font-size: 65px;
  padding-top: 15px;
  font-weight: 400;
  text-transform: uppercase;
}
.imagem_calendario {
  display: flex;
  width: 32px;
  height: 32px;
  padding: 0px 5.333px 5.333px 0px;
  align-items: center;
}
</style>