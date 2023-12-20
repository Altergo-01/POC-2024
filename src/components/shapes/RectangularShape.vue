<script>
 

export default {
  data() {
    return {
      
    };
  },
  methods: {


  },

};
</script>
<template>    

  <div id="img-content" class="WrapperShape">
    
    <div  class="Rect-left">
      <img src="@/assets/Home-shape.png" alt="">
    </div>
    
    <p class="Rect-right">
      <span>Notre projet de configurateur de cuisine marque une révolution dans l'expérience immersive et la simulation tridimensionnelle accessible à tous, directement depuis votre navigateur web. </span>    
      <span>Imaginez une cuisine conçue sur mesure, taillée selon vos préférences, et adaptée à la perfection à votre style de vie. Avec notre configurateur, cette vision devient réalité. Peu importe la taille de votre espace, notre outil ingénieux permet de créer une cuisine fonctionnelle, esthétique et parfaitement ajustée à votre environnement. Chaque détail, du choix des blocs de rangement à la disposition des éléments, peut être personnalisé pour répondre à vos exigences uniques.</span>
      <span>Notre futur interface conviviale et intuitive rendra le processus de conception ludique et accessible à tous. Il vous accompagnera dans chaque étape, faisant de la création de votre cuisine idéale une expérience agréable et sans tracas.</span>
      <span>Nous croyons en l'innovation au service de la facilité d'utilisation, c'est pourquoi notre configurateur repousse les limites de la technologie pour vous offrir une expérience immersive exceptionnelle.</span>
    </p>
 
  </div>

</template>

<style scoped>

svg {
  height: 100%;
  width: 50%;
}
span {

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
  font-size: 0.875rem;
  row-gap: 1rem;
}

.Shape-bg{
  width: 100%;
}

.Rect-txt span {
  margin-left: 20%;
}

.Rect-txt::before{
  content: "";
  width: 100%;
  height: 100%;
  background-size: cover;
  background-image: url('@/assets/Rect.png');
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

</style>