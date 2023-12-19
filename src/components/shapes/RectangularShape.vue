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

  <div id="img-content" class="imgC">
 
    <img src="@/assets/Rect-img.png" alt="" class="Rect-left">
    <p class="Rect-right">
      <img src="@/assets/Rect.png" alt="" class="Shape-bg" >
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
    position: absolute;
    top: 10%;
    left: 15%;
    right: 5%;
}
.imgC{
  display: flex;
  justify-content: center;
  align-items: center;
  column-gap: none;
  height: fit-content;
}

.Rect-left{
  height: 100%;
  width: 50%;
}
.Rect-right{
  height: 100%;
  width: 50%;
  margin-block-end: 0px;
  margin-block-start: 0px;
  position: relative;
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