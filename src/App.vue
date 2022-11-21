<template>
  <HeaderComponent />
  <main>
    <CardsComponent/>
  </main>
  <FooterComponent />

</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import CardsComponent from './components/CardsComponent.vue';


export default {
  components: {
    HeaderComponent,
    CardsComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">
//@use './assets/styles/general.scss' as *;

// h1 {
//   color: $colorred;
// }
</style>