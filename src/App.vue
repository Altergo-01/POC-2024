<script setup>
import { RouterLink, RouterView } from 'vue-router'
import BarNav from '@/components/BarNav.vue';
import Rectangular from './components/shapes/RectangularShape.vue';
import UpdateComp from './components/UpdateComp.vue';
import CardSub from '@/components/shapes/CardSub.vue'
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
    <div class="ProjetTitle">
      <h2>LE PROJET</h2>
      <p>Pour améliorer votre expérience.</p>
    </div>

    <Rectangular></Rectangular>
  </section>

  <main>
    <section class="Content">

      <article class="Actu">
        <h2>ACTUALITÉS</h2>
        <div class="ActuList">

        </div>
      </article>



    </section>

    <section class="CardSub">
      <div style="height: 20vh">&nbsp;</div>
      <h2> Contreparties </h2>

      <CardSub CardTe="On test en sah" CardIc="../src/assets/testCardImg.png" CardNa="testo" CardPr="25"></CardSub>
    </section>
  </main>

 

</template>




<style scoped>



video {
    width: 100%;
    z-index: -1;
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

section.heroVod {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}


.ProjetIntro{
  display: flex;
  flex-direction: column;
  column-gap: 0rem;
  justify-content: center;
  align-items: center;
  background-color: var(--color-cream-N);
  height: 60vh;
}

.ProjetTitle{
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  padding-left: 15%;
  width: 100%;
  height: 15%;
  margin-bottom: 1rem;
}

.ProjetTitle p{
  color: #925335;
  font-weight: bold;
}

main{
  display: flex;
  justify-content: center;
  align-items: start;
  height: fit-content;
  margin-top: 15vh;
}
.CardSub{
  height: fit-content;
  width: 20%;
}

.CardSub h2{
  margin-bottom: 4vh;
}

.Content {
    width: 75%;
    display: flex;
    align-items: flex-start;
    justify-content: center;
}

.Actu{
  width: 100%;
  padding: 0 0 0 15%;
  border-left: 1px solid rgb(42, 42, 42);
}

.Actu h2{
  margin-bottom: 5vh;
  

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
