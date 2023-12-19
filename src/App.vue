<script setup>
import { RouterLink, RouterView } from 'vue-router'
import BarNav from '@/components/BarNav.vue';
import Rectangular from './components/shapes/RectangularShape.vue';
import UpdateComp from './components/UpdateComp.vue';
</script>

<template>
 
  <header>
      
    <BarNav></BarNav>
 
  </header>


  <section class="heroVod">
    <div  class="leftVodInfo">

    </div>
    <video autoplay muted loop >
      <source src="@/assets/demo_configurateur.mp4" type="video/mp4">
    </video>
  </section>
 

  <section class="ProjetIntro">

  </section>
 

</template>




<style scoped>

video {
    width: 100%;
}
 
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;

}

section.hero-vod {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}


.ProjetIntro{
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--color-cream-N);
  height: 50vh;
}



@media (min-width: 1024px) {
  header {
    display: flex;
 
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
    height: 20vh;
  }

}
</style>
