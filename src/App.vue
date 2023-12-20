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
 

  <section class="ProjetIntro" id="p1">
    <div class="ProjetTitle">
      <h2>LE PROJET</h2>
      <p>Pour améliorer votre expérience.</p>
    </div>

    <Rectangular></Rectangular>
  </section>

  <main>
    <section class="Content" >

      <article class="Actu" id="p2">
        <h2>ACTUALITÉS</h2>
        <div class="ActuList">
          <UpdateComp date1="10" date2="Décembre 2023" Mess1="Merci Beaucoup... Le palier des 50000€ a été atteint en quelques jours." Com1="La réalisation du projet est enfin possible et nous allons pouvoir commencer à travailler dessus. Merci beaucoup pour votre contribution au projet." Com2="'On commencera le projet en bonne et du forme et on le présentera comme tel'"> 
          </UpdateComp>
          <UpdateComp date1="8" date2="Janvier 2024" Mess1="Avancée... Nous voulons vous tenir au courant que le projet avance bien, nous avons déjà bien entammer la réalisation des différents modéles 3D." Com1="Nous avons aussi commencer à réaliser toutes la préconfiguration du projet au niveau du site internet et des 
solutions utilisées pour la mise à bien du modulateur de cuisine." Com2="Merci infiniment de votre soutient, on va tout donner pour ne pas vous décevoir"> 
          </UpdateComp>
          <UpdateComp date1="26" date2="Janvier 2024" Mess1="Incroyable...

1 mois plus tard nous avons réussi à dépasser le deuxième palier et atteint un peu plus de 70000€." Com1="Merci à toutes les personnes qui ont souhaités nous soutenir sur ce projet et grâce à vous,
l'ambition est d'autant plus grande et nous nous efforçons de réaliser un projet au summum de vos attentes." Com2="Spectaculaire, on a plus aucune raison de ne pas réaliser un projet aussi bien travailler avec autant de personne qui nous soutiennent, merci à tous."> 
          </UpdateComp>

          
        </div>
      </article>

      <article class="ProjetSteps Particle" id="p3">

    

        <h2> PALIERS </h2>
            <img src="@/assets/StepsProject.png" alt="" width="90%">
        <h3>Palier 1</h3>
        <br>
        <p>Dans la première itération du configurateur, nous vous proposons une sélection de cuisines préfabriquées tout en vous laissant la liberté de personnaliser les matériaux, les couleurs, ainsi que les modèles de poignées et de façades selon vos préférences.</p>

                
        <h3>Palier 2</h3>
        <br>
        <p>Nous repoussons les limites du configurateur pour vous offrir la possibilité de concevoir entièrement votre cuisine. Vous pouvez désormais choisir la taille de votre espace cuisine et décider où positionner chaque meuble, le tout grâce à une interface utilisateur totalement repensée, plus intuitive et complète.</p>

                
        <h3>Palier 3</h3>
        <br>
        <p> Nous perfectionnons le niveau de personnalisation en permettant la modification de la forme de la pièce et de ses angles. Cela s'adresse particulièrement aux cuisines aux agencements plus complexes. De plus, nous introduisons un nouvel onglet "cosmétiques" qui vous donne la liberté d'ajouter des éléments décoratifs pour une immersion totale dans votre projet.</p>

                
        <h3>Palier 4</h3>
        <br>
        <p>À ce stade, vous avez la possibilité de créer vos propres meubles de A à Z. Choisissez la taille, la profondeur, la hauteur, le nombre de tiroirs, et bien plus encore. Une fois votre création aboutie, nous ajoutons automatiquement les détails de sa fabrication à votre panier, vous offrant une expérience de personnalisation ultime pour votre cuisine.</p>

                
        <h3>Palier ???</h3>
        <br>
        <p>?????????</p>

      </article>

      <article class="ProjetDetail Particle">
        <h2> NOTRE AVENTURE AVEC TIDYS </h2>
        <p>Le projet du modulateur de cuisine réaliser pour Tidys est un projet qui nous tenais à coeur. <br><br>
En tant que Kitchen Engineers, nous recherchions un collaborateur afin de nous soumettre un projet qui répondait à nos critéres. <br>
Ce projet va permettre au particulier de se projeter dans leurs propres cuisine de types IKEA et de designer eux même leurs meubles,
avec les matériaux proposer par Tidys.</p>
      </article>

      <article class="ProjetGoal Particle">
        <h3>Un grand merci à tous ceux qui compte nous soutenir. <br><br> Vous êtes une partie vitale de notre ascension, du progrès 
        de ce projet, et c'est avec grand plaisir que nous vous accompagnerons régulièrement sur nos avancée, et les projets futurs que vos 
      participation permettront de faire naître.</h3>

      <br>

      <h3> L'équipe KitchenEngineer</h3>
      </article>

      <article class="Particle"></article>

    </section>

    <section class="CardSub">
      <div style="height: 20vh">&nbsp;</div>
      <h2> Contreparties </h2>

      <CardSub CardTe="Donne accès à une carte fidélité exclusive, offrant -30% sur le 11ème produit acheté chez Tidys, badges Tidys fait avec les matériaux des façades. ( choisir )" CardIc="/src/assets/CTP1.png" CardNa="Carte Artisan" CardPr="5"></CardSub>

      <CardSub CardTe="Permet d'être traité en priorité pour une commande future et assure la qualité dans un délais record." CardIc="/src/assets/CTP2.png" CardNa="Carte Coupe-file" CardPr="20"></CardSub>

      <CardSub CardTe="Permet d'avoir accès aux nouveau produit en avance sur le site + récompenses précédentes." CardIc="/src/assets/CTP3.png" CardNa="Carte Associé" CardPr="50"></CardSub>

      <CardSub CardTe="Permet d'être immortalisé comme l'un des pilier du service Tidys sur le site, -25% sur la totalité de la première commande" CardIc="/src/assets/CTP4.png" CardNa="Carte Colaborateur" CardPr="100"></CardSub>

      <CardSub CardTe="Accès à des exemplaire gratuit de nouveaux produit, et permet de voir ses avis et conseils pris en compte, pour accompagner Tidys dans sa poursuite de la qualité. " CardIc="/src/assets/CTP5.png" CardNa="Carte Prestige" CardPr="250"></CardSub>


    </section>
  </main>

 

</template>




<style scoped>

.Particle{
  margin-top: 20vh;
  padding: 0 15vh 0 10vh;
}

.Particle h2{
  margin: 0 0 5vh 0;
}
.Particle h3{
  color: #925335;
  margin-top: 5vh;
}


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
    flex-direction: column ;
    align-items: flex-start;
    justify-content: center;
    row-gap: 5vh;
}

.Actu{
  width: 100%;
  padding: 0 0 0 5%;
  
}

.Actu h2{
  margin: 0 0 5vh 5vh;
  

}

.ActuList{
  border-left: 2px solid rgb(211 211 211);
  padding: 0 0 0 2%;
  display: flex;
  flex-direction: column;
  row-gap: 3vw;
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
