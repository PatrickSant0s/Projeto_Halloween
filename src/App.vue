<template>
  <div>
    <MenuPrincipal/>
    <PaginaPrincipal/>
    <GaleriaPrincipal/>
    <IngressoELocal/>
    <CaracteristicasEvento/> 
    <Ticket/>
  </div>

</template>

<script>
import MenuPrincipal from '@/components/MenuPrincipal.vue';
import PaginaPrincipal from '@/components/PaginaPrincipal.vue';
import GaleriaPrincipal from '@/components/Galeria.vue';
import IngressoELocal from '@/components/IngressoDoEvento.vue';
import CaracteristicasEvento from '@/components/CaracteristicasDoEvento.vue';
import Ticket from '@/components/TicketEValores.vue'
export default {
  name:"app",
  components: { MenuPrincipal, PaginaPrincipal, GaleriaPrincipal,IngressoELocal,CaracteristicasEvento, Ticket}

}
</script>

<style>

#app {

}
</style>


