<script>


export default {
  props: ['CardIc', 'CardNa', 'CardTe', 'CardPr'],
  data() {
    return {

    };
  },
  methods: {

  },
  mounted() {
    console.log(this.CardIc);
  }

};
</script>
<template>
  <div class="CardContainer">
    <!-- <div class="CardContent"></div> -->
    <div class="CardIcon">
      <img :src="this.CardIc" :alt="CardIc">
      <h2>{{ CardPr }}€ &nbsp; </h2>
    </div>

    <div class="CardText">
      <h3>{{ CardNa }}</h3>
      <br>
      <p>{{ CardTe }}</p>

    </div>
  </div>
</template>

<style scoped>
/* .CardContainer{
  width: 20vw;
  height: 25.6vw;
  box-shadow: 0 1px 0 0 rgba(106, 106, 106, 0.41) ;
} */

/* .CardContainer::before{
  content: "";
    background-image: url(/src/assets/iridescent.png);
    position: absolute;
    z-index: -1;
    background-repeat: no-repeat;
    background-size: cover;
    width: inherit;
    height: inherit;
    border-radius: 1.25rem;
} */

.CardContainer {
  background-color: var(--color-cream-N);
  border-radius: 1.25rem;
  height: 25vw;
  width: 18vw;
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  column-gap: 3%;
  padding: 3% 0px;
  align-items: center;
  margin-bottom: 5vh;
}

.CardIcon {
  position: relative;
  width: 90%;
  height: fit-content;
}

.CardIcon img {
  width: 100%;
}

.CardIcon h2 {
  font-size: 1.5vw;
  position: absolute;
  right: 0;
  bottom: 2px;
}

.CardText {
  width: 90%;

}

.CardText p {
  font-size: 0.80vw;
}
</style>