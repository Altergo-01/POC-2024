<script>
 import arrow from "../assets/Arrow.png"
import arrowW from "../assets/ArrowWhite.png"

export default {
    
  props: ['date1', 'date2', 'Mess1', 'Com1', 'Com2'],
  data() {
    return {

        deploy:false,
        trueHeight:'',
    };
  },
  methods: {

    deployed(){
         this.deploy = !this.deploy
    },

    getInfoRectContentHeight() {
        this.trueHeight = document.querySelector('.Info-text').offsetHeight;
        console.log(this.trueHeight)
    },

    pxToVW(px) {
        return (px+30) / window.innerWidth * 100;
    },

  },
  computed: {
    getWrapperHeight() {
        return {
            height: this.deploy ? this.pxToVW(this.trueHeight) + "vw" : '8vw',
           
        };
         
    },

    getArrowImage() {
    return this.deploy ? arrowW : arrow;
  },
},

mounted() {
  this.getInfoRectContentHeight();
}

};
</script>

<template>    

    <section class="Wrapper-shapes"  :style="getWrapperHeight">

         
            <div class="Info-square">
                <h2>{{ date1 }}</h2>
                <p> {{ date2 }}</p>
            </div>
        
   
        <div class="Wrapper-rt">
            <div class="Info-rect">
                <p class="Info-text"> 
                    {{ Mess1 }}
                    <br><br>
                    {{ Com1 }}
                    <br><br>
                    <p>Un message de toute l'équipe :</p>
                    <br><br>
                    {{ Com2 }}
                </p>
                <img  :src="this.getArrowImage" v-on:click.prevent="deployed()" class="Info-deploy"> 
            </div>

        </div>

      

    </section>

</template>

<style scoped>




.Wrapper-shapes{
    
    display: flex;
    width: 100%;
    height: vw;
    transition: height 0.2s ease;
}

 
.Info-square{
    height: 100%;
    width: 8vw;
    background-color: var(--color-mr-N);
    border-radius: 1rem 0px 1rem 1rem;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.Info-square h2 {
    font-size: 1.5vw;
}

.Info-square p {
    font-size: 1rem;
    text-align: center;
    margin-top: 5%;
}

.Wrapper-rt{
  
    display: flex;
    background-color: #2b150c;
    padding: 0.5rem 0 0 0;
    border-radius: 0 0.5rem 0 0;
    height: 100%;
    width: 50vw;

}

.Info-rect {
    background-color: white;
    border-radius: 1rem 0 0 0;
    padding: 0.5rem;
    position: relative;
    overflow: hidden;
}

.Info-deploy{
    position: absolute;
    right: 3vw;
    top: 50%;
}

.Info-text{
    width: 85%;
    margin-left: 3%;
}

</style>