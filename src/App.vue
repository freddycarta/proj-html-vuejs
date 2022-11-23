<template>
  <HeaderComponent />
  <main>
    <CardsComponent/>
    <VideoLiveComponent/>
  </main>
  <FooterComponent />

</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import CardsComponent from './components/CardsComponent.vue';
import VideoLiveComponent from './components/VideoLiveComponent.vue';


export default {
  components: {
    HeaderComponent,
    CardsComponent,
    VideoLiveComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">

</style>