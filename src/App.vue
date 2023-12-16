<script setup>
import { RouterLink, RouterView } from 'vue-router'
import BarNav from '@/components/BarNav.vue';
import Rectangular from './components/shapes/Rectangular.vue';
import UpdateComp from './components/UpdateComp.vue';
</script>

<template>
  <BarNav></BarNav>
  <header>
      

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
      </nav>
    </div>
  </header>

  <!-- <RouterView /> -->

<Rectangular> </Rectangular>

<br><br><br>

<UpdateComp> </UpdateComp>

<br><br><br>


</template>

<style scoped>


 
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


@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
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
