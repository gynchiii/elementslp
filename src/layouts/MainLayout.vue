<template>
    <q-layout>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Orbitron&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Alfa+Slab+One&family=Allerta+Stencil&family=Audiowide&display=swap');

.texxt{
  font-family: 'Orbitron', sans-serif;

}
.texxt2{
  font-family: 'Alfa Slab One', cursive;
  font-family: 'Allerta Stencil', sans-serif;
  font-family: 'Audiowide', cursive;
}
</style>

<script>

export default {
  name: 'MainLayout',
  data () {
    return {
      leftDrawerOpen: false,
    }
  }
}
</script>
