<template>
    <iframe class="embed-responsive-item youtube" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0"></iframe>
    <div class="container">
        <div class="text-center">
        <h1>Live Dates</h1>
        <hr>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti expedita non officia et, ex ad eius inventore est nostrum natus quaerat, reiciendis nobis, odit at ipsum fuga alias accusantium sit?</p>
        <ul>
            <li class="display-6"><i class="fa-regular fa-square-plus"></i><a href="">17/07/08 NEW YORK - YANKEE STADIUM</a></li>
            <li class="display-6"><i class="fa-regular fa-square-plus"></i><a href="">08/08/22 BERGAMO - ORIO AL SERIO</a></li>
            <li class="display-6"><i class="fa-regular fa-square-plus"></i><a href="">19/19/23 MILANO - BAGNO DI CASA MIA</a></li>
            <li class="display-6"><i class="fa-regular fa-square-plus"></i><a href="">2000ECREDICI - NARNIA - ARMADIO</a></li>
        </ul>
    </div>



    </div>


</template>

<script>
export default {
    name: 'VideoLiveComponent',
    data() {
        return {
          
        }
    },
    methods: {

    }
}
</script>

<style lang="scss" scoped>
    .youtube {
  width:100%;
  height: 500px;
}

li {
    list-style: none;
    
}

a {
    color: black;
    background-color: #ec4958;
    text-decoration: none;
    
    

}
</style>