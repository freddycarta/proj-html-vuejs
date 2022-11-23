<template>
    <header>
        <nav class="navbar">
            <div class="container-fluid d-flex">
                <div class="navbar-brand d-flex justify-content-between text-white"  href="#">
                <img src="../assets/img/logo_footer.png" alt="" >
                </div>
                <nav class="navbar navbar-light">
    <div class="container-fluid">
      <button class="navbar-toggler ms-auto text-white" type="button" data-mdb-toggle="collapse"
        data-mdb-target="#navbarToggleExternalContent3" aria-controls="navbarToggleExternalContent3"
        aria-expanded="false" aria-label="Toggle navigation">
        <i class="fas fa-bars"></i>
      </button>
    </div>
  </nav>
  <div class="collapse" id="navbarToggleExternalContent3">
    <div class="bg-light  p-4">
      <button class="btn btn-link btn-block border-bottom m-0">Link 1</button>
      <button class="btn btn-link btn-block border-bottom m-0">Link 2</button>
      <button class="btn btn-link btn-block m-0">Link 3</button>
    </div>
  </div>
                
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

    <div class="text-center">
        <h1>Music is life</h1>
        <p class="container">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti expedita non officia et, ex ad eius inventore est nostrum natus quaerat, reiciendis nobis, odit at ipsum fuga alias accusantium sit?</p>
        <hr>
    </div>
    
</template>

<script>

export default {
    name: 'HeaderComponent',
    data() {
        return {
         
        }
    },
    methods: {

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

.navbar {
position: fixed;
  top:0;
  width: 100%;
  height: 60px;
  line-height: 60px;
}

h1 {
    margin-top: 100px;
}

</style>