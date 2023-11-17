<template>
  <div class="container">
    <h1 class="party">Party Time!</h1>
    <nav class="menu-principal">
    
     <a :href="menu.href" :key="menu.titulo" v-for="menu in menuDeNavegacao">{{ menu.titulo }}</a>   
    </nav>
    <div class="botao">
      <button class="botao-reserva">Reservation</button>
    </div>
  </div>
</template>


<script>
export default {
  name: "MenuPrincipal",
  data() {
    return {
      menuDeNavegacao: [{ titulo: "Home", href: "" },{ titulo: "Gallery", href: "" },{ titulo: "About Party", href: "" },{ titulo: "Reservation", href: "" },
      { titulo: "Contacts", href: "" }
    ],
    };
  },
};
</script>


<style scoped>
h1 {
  font-family: var(--fonte-principal);
  color: var(--color-texto-secudario);
  font-size: 48px;
  font-style: normal;
  font-weight: 400;
}

.menu-principal {
  display: grid;
  grid-template-columns: repeat(5, 100px);
  gap: 10px;
  justify-items: center;
}
a {
  text-decoration: none;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  text-transform: capitalize;
  font-family: var(--fonte-secundaria);
  line-height: 150.4%;
  color: #f5f5f5;
}
.botao-reserva {
  padding: 16px 24px;
  border-radius: 16px;
  color: #292d32;
  background: var(--color-principal);
  cursor: pointer;
}
.container {
  margin-top: 40px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  align-content: space-between;
  text-align: center;
  justify-content: center;
  align-items: center;
}
</style>