<template>
    <div class="hosts">
        <h1 class=" titulo-planos titulo-join">Let's be your hosts </h1>
            <div class="planos">
                <ul class="listagem-planos">
                    <li class="cartao-plano">

                        <div class="informacao">
                            <span class="single">Combine Ticket</span>
                            <span class="valor">$300</span>

                            <div class="descricao-plano">
                                <p>Blood Drink </p>
                                <p>Haunted House Tour</p>
                                <p>Horror Movie Marathon</p>
                            </div>

                            <div class="botao ">

                                <button class="bota-ticket">Buy Ticket</button>
                            </div>


                        </div>
                    </li>

                </ul>
                <ul class="listagem-planosDois">
                    <li class="cartao-plano">

                        <div class="informacao">
                            <span class="single">Single Ticket</span>
                            <span class="valor">$100</span>

                            <div class="descricao-plano">
                                <p>Blood Drink </p>
                                <p>Haunted House Tour</p>
                                <p>Horror Movie Marathon</p>
                            </div>

                            <div class="botao ">

                                <button class="bota-ticket">Buy Ticket</button>
                            </div>
                        </div>
                    </li>

                </ul>
            </div>
    </div>
</template>

<script>
export default {
  name: "TicketEValores"
};
</script>



<style scoped>
.planos {
    display: grid;
    grid-template-areas: "esquerda  direita";
    justify-content: space-around;
}


.listagem-planos {
    grid-column: 2/3;
}

.listagem-planosDois {
    grid-row: 1;
}

.titulo-planos {
    margin: 0 0 40px;
}


.cartao-plano {
    width: 344px;
    height: 464px;
    border-radius: 50px;
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.20) 0%, rgba(0, 0, 0, 0.20) 100%), var(--Gray, #333);
    width: 344px;
    height: 464px;

}


.informacao {
    display: grid;
    text-align: center;
    justify-content: center;
    justify-items: center;
    padding: 20px 0px 20px 0px;



}

.single {
    color: var(--White, #F9F9F9);
    text-align: center;
    font-family: var(--fonte-principal);
    font-size: 36px;
    font-style: normal;
    font-weight: 400;
    text-transform: capitalize;
    padding: 16px;
}

.valor {
    color: #F9F9F9;
    text-align: center;
    font-family: 'Montserrat', sans-serif;
    font-size: 40px;
    font-style: normal;
    font-weight: 700;
    text-transform: uppercase;
}

.descricao-plano p {
    color: var(--White, #F9F9F9);
    text-align: center;
    font-family: var(--fonte-secundaria);
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    text-transform: capitalize;
    margin: 43px;

}

.bota-ticket {
    padding: 16px 78px;
    align-items: flex-start;
    gap: 8px;
    border-radius: 16px;
    background-color: var(--color-principal);
    color: #131313;
    font-family: var(--fonte-secundaria);
    font-weight: 500;
    text-align: center;
    cursor: pointer;
}
</style>

