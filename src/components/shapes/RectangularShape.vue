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
      <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas sapiente hic perspiciatis voluptates aspernatur suscipit. Qui, reiciendis dolorem sunt perferendis, sint quos dolor temporibus, repudiandae eveniet rem facere minus quibusdam?</span>    
      <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas sapiente hic perspiciatis voluptates aspernatur suscipit. Qui, reiciendis dolorem sunt perferendis, sint quos dolor temporibus, repudiandae eveniet rem facere minus quibusdam?</span>    
      <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas sapiente hic perspiciatis voluptates aspernatur suscipit. Qui, reiciendis dolorem sunt perferendis, sint quos dolor temporibus, repudiandae eveniet rem facere minus quibusdam?</span>    
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