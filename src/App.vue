<template>
  <div>
    <MenuPrincipal/>
    <PaginaPrincipal/>
    <GaleriaPrincipal/>
  </div> 
  

</template>

<script>
import MenuPrincipal from '@/components/MenuPrincipal.vue';
import PaginaPrincipal from '@/components/PaginaPrincipal.vue';
import GaleriaPrincipal from '@/components/Galeria.vue';

export default {
  name:"app",
  components: { MenuPrincipal, PaginaPrincipal, GaleriaPrincipal }

}
</script>

<style>

#app {
  
}
</style>


