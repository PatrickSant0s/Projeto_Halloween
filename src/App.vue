<template>
  <div>
    <MenuPrincipal/>
    <PaginaPrincipal/>
    <GaleriaPrincipal/>
    <IngressoELocal/>
    <CaracteristicasEvento/> 
  </div>

</template>

<script>
import MenuPrincipal from '@/components/MenuPrincipal.vue';
import PaginaPrincipal from '@/components/PaginaPrincipal.vue';
import GaleriaPrincipal from '@/components/Galeria.vue';
import IngressoELocal from '@/components/Ingresso.vue'
import CaracteristicasEvento from '@/components/caracteristicas.vue'
export default {
  name:"app",
  components: { MenuPrincipal, PaginaPrincipal, GaleriaPrincipal,IngressoELocal, CaracteristicasEvento }

}
</script>

<style>

#app {

}
</style>


