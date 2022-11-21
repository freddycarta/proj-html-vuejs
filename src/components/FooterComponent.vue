<template>
    <footer>
        <div class="cols container">
            <a href="#" class="logo">
                <img src="../assets/img/logo_footer.png">
            </a>
            <FooterMenu v-for="(menu, index) in navBars" :key="index" :item="menu" />

        </div>

    </footer>
</template>

<script>
import { menu } from '../data/products';
import FooterMenu from './FooterMenu.vue';
export default {
    name: 'FooterComponent',
    components: {
        FooterMenu
    },
    data() {
        return {
            navBars: menu
        }
    }
}
</script>

<style lang="scss">
@use '../assets/styles/partials/mixins' as *;
@use '../assets/styles/partials/variables' as *;

footer {

    .cols {
        display: flex;


        .logo,
        // .footer-links {
        //     flex-basis: calc(100% / 3);
        
        // }

        ul {
            list-style: none;

            li a {
                display: inline-block;
                margin-bottom: 0.25rem;
                text-decoration: none;
                font-size: 0.875em;

            }
        }
    }
}
</style>