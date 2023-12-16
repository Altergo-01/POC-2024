<script>
import { textInShape } from 'text-in-shape';
import iridescent from '@/assets/iridescent.png';
import wrap from 'text-in-shape';

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

    <section class="Wrapper-shapes">

        <div class="Wrapper-sq">
            <div class="Info-square">
                <h2>ererer</h2>
                <p>grezrzerrztzert zrtzret</p>
            </div>
        </div>
   
        <div class="Wrapper-rt">
            <div class="Info-rect">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Impedit quis facere eveniet dicta iure alias 
                    magni natus cumque nihil, sit modi obcaecati dolorem est omnis culpa, incidunt praesentium minus necessitatibus?
                </p>
            </div>
        </div>


    </section>

</template>

<style scoped>


.Wrapper-shapes{
    display: flex;
    width: 80vw;
    height: 10vw;
}


.Wrapper-sq{

}
.Info-square{
    height: 10vw;
    width: 10vw;
    background-color: var(--color-mr-N);
    border-radius: 1rem 0px 1rem 1rem;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.Wrapper-rt{
    display: flex;
    background-color: #2b150c;
    padding: 0.5rem 0 0 0;
    border-radius: 0 0.5rem 0 0;
}

.Info-rect {
    background-color: white;
    border-radius: 1rem 0 0 0;
    padding: 0.5rem;
}


</style>