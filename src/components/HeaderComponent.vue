<template>
    <header>
        <SiteLogo />
      <nav>
        <a href="#">Home</a>
        <a href="#" class="active">Prodotti</a>
        <a href="#">Chi Siamo</a>
        <a href="#">Contatti</a>
      </nav>
    </header>
</template>

<script>
import SiteLogo from '@/components/LogoComponent';
export default {
    name: 'HeaderComponent',
    components: {
        SiteLogo
    }
}
</script>

<style lang="scss" scoped>
@import '@/assets/sass/variables';
header  {
    text-align: center;
     nav {
        margin: 2rem 0;

        a {
            padding: 0.5rem 1rem;
            text-decoration: none;
            font-size: 0.9rem;
            color: $brandColor;
            font-weight: 600;

            &.active {
                background-color: $brandColor_4;
            }
            &:hover {
                background-color: rgb(210, 236, 245) ;
            }
        }
    }
 
}
  
</style>