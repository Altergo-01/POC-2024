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

  <div id="img-content" class="imgC">
    <!-- <div class="stop-start"></div> 
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 815 347" fill="none" class="Rect-img">
      <path d="M43 7.33281e-07C19.2517 3.28301e-07 0 19.2518 0 43L0 304C0 327.748 19.2518 347 43 347L693.76 347C717.508 347 736.76 327.748 736.76 304V204.199C736.76 183.422 753.603 166.579 774.38 166.579V166.579C795.157 166.579 812 149.736 812 128.959V43.4839C812 19.7357 792.748 0.48397 769 0.48397L652.497 0.48397L545.404 9.3008e-06L43 7.33281e-07Z" fill="url(#pattern0)"/>
      <defs>
        <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
          <use xlink:href="#irid" transform="matrix(0 -0.000607533 0.00142166 0 -0.15823 1)"/>
        </pattern>
        <image id="irid" width="1646" height="926" href="@/assets/iridescent.png"></image>

      </defs>
    </svg>-->
    <img src="@/assets/Rect-img.png" alt="" class="Rect-left">
    <p class="Rect-right">
      <img src="@/assets/Rect.png" alt="" class="Shape-bg" >
      <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas sapiente hic perspiciatis voluptates aspernatur suscipit. Qui, reiciendis dolorem sunt perferendis, sint quos dolor temporibus, repudiandae eveniet rem facere minus quibusdam?</span>    
    </p>
<!-- 
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 815 347" fill="none" class="Rect-img">
      <path d="M43 7.33281e-07C19.2517 3.28301e-07 0 19.2518 0 43L0 304C0 327.748 19.2518 347 43 347L693.76 347C717.508 347 736.76 327.748 736.76 304V204.199C736.76 183.422 753.603 166.579 774.38 166.579V166.579C795.157 166.579 812 149.736 812 128.959V43.4839C812 19.7357 792.748 0.48397 769 0.48397L652.497 0.48397L545.404 9.3008e-06L43 7.33281e-07Z" fill="url(#pattern0)"/>
      <defs>
        <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
          <use xlink:href="#irid" transform="matrix(0 -0.000607533 0.00142166 0 -0.15823 1)"/>
        </pattern>
        <image id="irid" width="1646" height="926" href="@/assets/iridescent.png"></image>

      </defs>
    </svg>

    <svg id="" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 815 347"   fill="none" reserveAspectRatio="xMinYMin meet" class="Rect-txt">
      <path d="M769 347C792.748 347 812 327.748 812 304L812 43C812 19.2518 792.748 -2.29575e-07 769 -5.1277e-07L118.24 -8.273e-06C94.4918 -8.5562e-06 75.24 19.2518 75.24 43L75.24 142.801C75.24 163.578 58.397 180.421 37.62 180.421V180.421C16.8431 180.421 2.33327e-05 197.264 2.30849e-05 218.041L2.20656e-05 303.516C2.17824e-05  327.264 19.2518 346.516 43 346.516L159.504 346.516L266.596 347L769 347Z"  fill="#21100A"/>
      <text x="250" y="150" font-family="Verdana" font-size="" fill="#FFFFFF">
          Bonjour tout le monde! Je suis nounours hihi, je veux ton trou hihi
      </text>
    </svg>
     -->

    <!-- <div class="stop-end"></div> -->
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