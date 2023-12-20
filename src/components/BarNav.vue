<script>
import ButtonClear from './ButtonClear.vue';

export default {
    components: {
        ButtonClear,
    },
    data() {
        return {
        
        };
    },
    methods: {

        
    },

};
</script>

<template>    

<nav >

    <div class="absolute-bg">

    </div>
    <div class="logo-mr">
        <img src="@/assets/logo.png" alt="">
    </div>
    <div class="prog-bar">
        <img src="@/assets/barre-prct.png" alt="">
    </div>
    <div class="nav-links">
        
        <ButtonClear buttonName="PROJET" idA="#p1"></ButtonClear>
         
        <ButtonClear buttonName="ACTUALITÉS" idA="#p2"></ButtonClear>

        <ButtonClear buttonName="PALIERS" idA="#p3"></ButtonClear>
   
    </div>

</nav>

</template>

<style scoped>

nav{
    position: relative;
    display: flex;
    height: 6vh;
    justify-content: space-between;
    background-color: var(--color-cream-N);
    column-gap: 3%;
    position: fixed;
    z-index: 1000;
    box-shadow: 0px 1px 11px 0px #9f9c9c82;
}

.logo-mr {
    width: 10%;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  
}

.logo-mr img{
    width: 6vw;
    margin-left: 2vw;
}

.prog-bar{
    width: 30%;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.prog-bar img{
    width: 90% ;
}

.absolute-bg{
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
    height: inherit;
}

.nav-links{
    display: flex;
    flex-direction: row;
    column-gap: 8%;
    width: 40%;
    justify-content: flex-end;
    justify-content: center;
    align-items: center;
    padding-right: 5%;
}

.nav-container{

}


</style>