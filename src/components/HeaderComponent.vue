<template>
    <header>
        <nav class="navbar">
            <div class="container-fluid d-flex">
                <div class="navbar-brand d-flex justify-content-between text-white"  href="#">
                <img src="../assets/img/logo_footer.png" alt="" >
                </div>
                <p class="d-flex justify-content-between display-6"><i class="fa-solid fa-bars"></i></p>
                
            </div>
        </nav>
        <div class=" container d-flex flex-column">
            <H1 class="text-white fw-bold display-1">Untold Stories</H1>
            <p class="text-white">There is un untold Story behind Every song</p>
            <div class="d-flex flex-wrap justify-content-center"><a class="btn btn-primary text-center ">Last Album</a>
            <a class="btn btn-primary text-center">Live Dates</a>
            </div>
        </div>
        


    </header>
    <div class="text-center bg-black">
        <h1>Music is life</h1>
        <p class="container">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti expedita non officia et, ex ad eius inventore est nostrum natus quaerat, reiciendis nobis, odit at ipsum fuga alias accusantium sit?</p>
    </div>
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
a {
    width: auto;
    border-radius: 5px;
    background-color: #ec4958;
    border: none;
    transition-duration: 0.4s;
    margin: 5px;
    color: white;
    font-size: larger;
}



.a.i:hover:hover {
  background-color: #af6f4c;
  color: white;
}

</style>