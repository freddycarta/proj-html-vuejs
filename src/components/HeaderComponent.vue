<template>
    <header>
        <nav class="navbar">
            <div class="container-fluid d-flex">
                <a class="navbar-brand d-flex justify-content-between text-white"  href="#">
                <img src="../assets/img/avada-music-logo-mobile-retina.png" alt="" width="30" height="24" >
                AVADA MUSIC
                </a>
                <p class="d-flex justify-content-between"><i class="fa-solid fa-bars"></i></p>
                
            </div>
        </nav>
        <div class="d-flex flex-column text-align-center">
            <H1 class="text-center text-white fw-bold">Untold Stories</H1>
            <p class="text-white">There is un untold Story behind Every song</p>
            <button>Latest Album</button>
            <button>New Dates</button>
        </div>

    </header>
</template>

<script>
import { links } from '../data/products.js'
export default {
    name: 'HeaderComponent',
    data() {
        return {
            image: '../assets/img/la-molisana-logo.png', //non funziona se non con metodo
            navbar: links
        }
    },
    methods: {
        //     getImageURL: function (imgPath) {
        //         return new URL(imgPath, import.meta.url).href;
        //     }
    }
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/mixins' as *;
@use '../assets/styles/partials/variables' as *;

header {
    text-align: center;
    background-image: url(../assets/img/home_slider.jpg);
    height: 80vh;
    background-repeat: no-repeat;
    background-size: cover;
    
    
}
button {
    width: 60px;
    border-radius: 5px;
    color: red;
    display: flex;
    flex-direction:row;
}

</style>