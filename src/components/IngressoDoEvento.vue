<template>
  <div>
    <h1 class="titulo-join">join us</h1>
    <h2 class="subtilo-join">this year’s Halloween Party!</h2>
    <p class="descricao">
      Our Halloween party this year will be an unforgettable experience, filled
      with spooky decorations, eerie music, thrilling games, and costume
      contests. Join us for a night of magic and fright!
    </p>
    <div class="ticket">
      <div class="ingressoEvento">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="48"
          height="48"
          viewBox="0 0 48 48"
          fill="none"
        >
          <path
            d="M34 41.5H14C5.18 41.5 2.5 38.82 2.5 30V29C2.5 28.18 3.18 27.5 4 27.5C5.92 27.5 7.5 25.92 7.5 24C7.5 22.08 5.92 20.5 4 20.5C3.18 20.5 2.5 19.82 2.5 19V18C2.5 9.18 5.18 6.5 14 6.5H34C42.82 6.5 45.5 9.18 45.5 18V20C45.5 20.82 44.82 21.5 44 21.5C42.08 21.5 40.5 23.08 40.5 25C40.5 26.92 42.08 28.5 44 28.5C44.82 28.5 45.5 29.18 45.5 30C45.5 38.82 42.82 41.5 34 41.5ZM5.5 30.32C5.54 37.2 6.96 38.5 14 38.5H34C40.68 38.5 42.3 37.32 42.48 31.32C39.62 30.64 37.5 28.06 37.5 25C37.5 21.94 39.64 19.36 42.5 18.68V18C42.5 10.86 41.16 9.5 34 9.5H14C6.96 9.5 5.54 10.8 5.5 17.68C8.36 18.36 10.5 20.94 10.5 24C10.5 27.06 8.36 29.64 5.5 30.32Z"
            fill="#E6EAEE"
          />
          <path
            d="M20 14.5C19.18 14.5 18.5 13.82 18.5 13V8C18.5 7.18 19.18 6.5 20 6.5C20.82 6.5 21.5 7.18 21.5 8V13C21.5 13.82 20.82 14.5 20 14.5Z"
            fill="#E6EAEE"
          />
          <path
            d="M20 29.16C19.18 29.16 18.5 28.48 18.5 27.66V20.32C18.5 19.5 19.18 18.82 20 18.82C20.82 18.82 21.5 19.5 21.5 20.32V27.66C21.5 28.5 20.82 29.16 20 29.16Z"
            fill="#E6EAEE"
          />
          <path
            d="M20 41.5C19.18 41.5 18.5 40.82 18.5 40V35C18.5 34.18 19.18 33.5 20 33.5C20.82 33.5 21.5 34.18 21.5 35V40C21.5 40.82 20.82 41.5 20 41.5Z"
            fill="#E6EAEE"
          />
        </svg>
      </div>
      <div class="endereco">
        <p>Tue, 31 Octobr 2023, 19:00</p>
        <p class="local">
          <img
            src="imagens/vuesax/outline/vuesax/outline/location.png"
            alt=""
          />The Menza Club, Istanbul city
        </p>
      </div>
    </div>
  </div>
</template>


<script>
export default {
    name:"IngressoDoEvento"
};
</script>



<style scoped>
.join {
    padding: 40px 0 40px 0;
    display: grid;
    flex-direction: column;
    grid-template-rows: 5, 1fr;
}

.titulo-join {
    text-align: center;
    text-transform: uppercase;
    color: var(--color-principal);
}

.subtilo-join {
    text-align: center;
    color: #FE2D2D;
    font-family: var(--fonte-principal);
    font-size: 58px;
}


.descricao {

    text-align: center;
    color: #fff;
    font-family: var(--fonte-secundaria);
    font-weight: 400;
    font-size: 24px;
    font-style: normal;
    text-transform: uppercase;
    padding: 48px;
}

/*ticket*/

.ticket {
    color: #E6EAEE;
    font-size: 20px;
    font-weight: 400;
    text-transform: capitalize;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;

}


.endereco {

    align-items: center;
    border-radius: 16px;
    border-top: 2px solid #E6EAEE;
    border-right: 2px solid #E6EAEE;
    border-bottom: 2px solid #E6EAEE;
    padding: 12px 24px;



}

.ingressoEvento {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 48px;
    height: 48px;
    padding: 12px 24px;
    border-radius: 16px;
    border-top: 2px solid #E6EAEE;
    border-bottom: 2px solid #E6EAEE;
    border-left: 2px solid #E6EAEE;

}
</style>