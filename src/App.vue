<script setup>
 
import BarNav from '@/components/BarNav.vue';
 
 
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
      <h2>ÉQUIPE KITCHEN ENGINEERS</h2>
      <p> POC Configurateur de cuisine</p>
    </div>

    <div id="img-content" class="WrapperShape">
    
    <div  class="Rect-left">
      <img src="./assets/Subtract.png" alt="">
    </div>
    
    <div class="Rect-right">
      <p>Matthias Petit</p>
      <span>Développeur Three.js et Intégrateur</span>
      <br>
      <p>Matthias Buczek</p>
      <span>Modélisateur blender et Chef de projet</span>
      <br>
      <p>Léo Teissier</p>
      <span>Modélisateur blender</span>
      <br>
      <p>Axel Bréhéret</p>
      <span>Intégrateur et maquetteur </span>
     
    </div>
 
  </div>
  </section>

  <section class="ProjetIntro"  >
    <div class="ProjetTitle">
      <h2>LE PROJET </h2>
      <p>Dans sa globalité technique, le commenditaire, et ce qu'il apporte</p>
    </div>

    <div id="img-content" class="WrapperShape">
    

    
    <div class="Rect-right">
       <p> ...</p>
    </div>

    <div  class="Rect-left">
      <img :src="'@/assets/'+Imgname" alt="">
    </div>
 
  </div>

  </section>
  <section class="ProjetIntro" id="p2">
    <div class="ProjetTitle">
      <h2>LA PRÉSENTATION VIDÉO</h2>
      <p>Dans un scénario pour le client comme le vendeur.</p>
    </div>

    <div id="img-content" class="WrapperShape">
    
        <h2>à venir...</h2>
      
  </div>
  </section>
  <section class="ProjetIntro" id="p4">
    <div class="ProjetTitle">
      <h2>ACCÉS EN LIGNE AU CONFIGURATEUR</h2>
      <p>Pour tenter de faire votre propre cuisine.</p>
    </div>

    <a href="https://mmi21d14.mmi-troyes.fr/wr501/" class="testing-ground"> <button> Essayez !</button>  </a>

    <div id="img-content" class="WrapperShape">
    

    
     

    <div  class="Rect-left">
      <img :src="'@/assets/'+Imgname" alt="">
    </div>
 
  </div>

  </section>
  <section class="ProjetIntro" id="p3">
    <div class="ProjetTitle">
      <h2>LE BILAN</h2>
      <p> Les fruits de ce POC et de ce qui pourrait être.</p>
    </div>

    <div id="img-content" class="WrapperShape">
    
    <div  class="Rect-left">
      <img src="./assets/Bilan.png" alt=""  id="imgBil">
    </div>
    
    <div class="Rect-right">
      <span>
        Notre production se concentre actuellement sur la modélisation 3D de cuisines IKEA. Initialement, nous envisagions de créer des ensembles prédéfinis pour des configurations
         typiques, telles que les cuisines en L ou avec îlot central. Cependant, nous avons révisé notre stratégie en reconnaissant qu'un configurateur basé sur des ensembles
          prédéfinis ne pourrait pas s'ajuster parfaitement à l'espace unique de chaque client potentiel, et ne satisfaisait pas la visio qu'avait Tidys des choses. <br><br>
          
          À l'avenir, nous ambitionnons de permettre l'importation directe de 
          la configuration de la cuisine d'un client via le modèle spécifique de sa cuisine. Cette approche d'importation éliminera le besoin pour le client de s'engager dans 
          le processus de configuration de base, lui permettant de se concentrer uniquement sur la sélection d'éléments esthétiques. Cette innovation promet un gain de temps 
          significatif pour le client. <br><br>
          
          Au cours du développement de ce projet, nous avons maintenu plusieurs interactions avec Tidys. Lors de notre dernier échange en visioconférence, nous leur avons présenté la version la plus récente de notre logiciel qui a été reçu avec enthousiasme, et en a profité pour recevoir leurs points de vue sur ce qui pourrait être ajouté dans le futur, ce qui aurait pu être amélioré, de la même manière que lors de nos entrevues visios précédentes.
          <br><br>

          

      </span>
    </div>
 
  </div>
  </section>
  <section class="ProjetIntro" id="p6">
    <div class="ProjetTitle">
      <h2>LE RETOUR DE TIDYS SUR LE POC</h2>
      <p> Des pistes, des projets, de l'enthousiasme.</p>
    </div>

    <div id="img-content" class="WrapperShape">
    

    
    <div class="Rect-right" id="bilan">
       <span>La réaction de notre commanditaire après notre dernier échange a été plus que positive. Inspirés par les progrès de notre POC, tout le long du semestre, ils ont exprimé un intérêt grandissant pour configurateur de cuisine. Un aperçu de qui pouvait être fait, même par un groupe aussi restreint que le nôtre, leurs à donné espoir de voir un jour cet outil intégré à leur processus de vente pour simplifier plusieurs étapes actuellement et généralement faites manuellement (comme l'annotation de chaque devis et des pièces commandée).
        <br><br>
        C'est dans cet élan de curiosité enthousiasmée qu'ils nous ont poussée de manière encourageante à d'explorer de nouvelles fonctionnalités, notamment le développement d'un configurateur meubles sur mesure en 3D, celui d'un panier automatique avec l'import d'un design de cuisine depuis un concurrent ou depuis le leurs et bien d'autres.
        <br><br> 
        Cette extension du projet reflète une confiance en nos compétences, une preuve de ce dont nous avons été capables et de ce qui aurait pu voir le jour, si la SAE avait duré plus longtemps, une chose pour laquelle l'équipe de Tidys nous à félicité. Le à nos accomplir en tant que développeurs, mais aussi en tant que membre du monde du multimédia, en démontrant nos compétences dans des domaines purement créatifs à ça , il s'agit d'une expérience que nous retiendrons collectivement comme un grand pas en avant.
     </span>
    </div>

 
 
  </div>

  </section>
   
 

</template>




<style scoped>


#imgBil{
  height: 75%;
   
}

#bilan{
  width: 70%;
}
.testing-ground{
  display: flex;
  justify-content: center;
  align-items: center;
  text-decoration: none;
  width: 70%;
  height: 65%;
  background-image: url('./assets/POCtesting.png');
  background-repeat: no-repeat;
  background-size: cover;
  margin-bottom: 3rem;
}

.testing-ground:visited, .testing-ground::after, .testing-ground:active{
  text-decoration: none;
}

.testing-ground button {
  color: #ffffff;
  font-weight: bold;
  font-size: 1.4rem;
  text-decoration: none;
  padding: 1.5rem 4rem;
  border-radius: 1rem;
  border: #ffffff solid 1px;
  background-color: #ffffff00;
  transition: 0.3s;
}

.testing-ground button:hover {
  color: #000000;
  border: #ffffff solid 1px;
  background-color: #ffffff;
}

svg {
  height: 100%;
  width: 50%;
}

.WrapperShape{
  display: flex;
  justify-content: center;
  align-items: center;
  column-gap: none;
  height: fit-content;
  column-gap: 0rem;
}

.Rect-left{
  height: 100%;
  width: 45%;
  display: flex;
  justify-content: center;
}

.Rect-left img{
  width: 70%;
}

.Rect-right{
  height: 100%;
  width: 45%;
  margin-block-end: 0px;
  margin-block-start: 0px;
  display: flex;
  flex-direction: column;
 
  justify-content: center;
  font-size: 0.875rem;
  row-gap: 0.2rem;
}

.Rect-right p{
  color: #925335;
  font-weight: bold;
  font-size: 1.2rem;
  margin-block-end: 0px;
  margin-block-start: 0px;
}

.Rect-right span {
  margin-block-end: 0px;
  margin-block-start: 0px;
  font-size: 1.2rem;
}

.Shape-bg{
  width: 100%;
}

.Rect-txt span {
  margin-left: 20%;
}


.stop-end{
  width: 10%;
  height: 100%;
  background-color: aqua;
  shape-outside: polygon(-47.11% 6px, 100% 50%, -47.89% 98.31%, -60px 45.35%);
}

.stop-start{
  width: 10%;
  height: 100%;
  background-color: aqua;
}
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
  margin-bottom: 5rem;
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
