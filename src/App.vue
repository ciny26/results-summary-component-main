<template>
  
   <BigContainer></BigContainer>
  
</template>

<script>
import BigContainer from './components/BigContainer.vue';
export default {
  name: 'App',
  components: {
    BigContainer
  }
}
</script>

<style>
:root{
  /*Light red:*/ 
  --Light_red:hsl(0, 100%, 67% );
  --Light_red_back:hsl(0, 100%, 67% , 0.3);
/*- Orangey yellow: */
--Orengy_Yellow:hsl(39, 100%, 56%);
--Orengy_Yellow_back:hsl(39, 100%, 56% , 0.3);
/*- Green teal: */
--green_teal:hsl(166, 100%, 37%);
--green_teal_back:hsl(166, 100%, 37% , 0.3);
/*- Cobalt blue:*/
--cobalt_blue: hsl(234, 85%, 45%);
--cobalt_blue_back: hsl(234, 85%, 45% , 0.5);

/* Gradients

- *//*Light slate blue (background):*/--light_slate_blue: hsl(252, 100%, 67%);
/*- Light royal blue (background): */--royal_blue:hsl(241, 81%, 54%);

/*- Violet blue (circle):*/--violet_blue: hsla(256, 72%, 46%, 1);
/*- Persian blue (circle):*/ --persian_blue:hsla(241, 72%, 46%, 0);
--Pale_blue: hsl(221, 100%, 96%);
--Light_lavender: hsl(241, 100%, 89%);
--Dark_gray_blue: hsl(224, 30%, 27%);
}
*{
  box-sizing: border-box;
  
}
html{
  height: 100%;
  width: 100%;
  max-width: 100%;
  max-height: 100%;
  overflow-x:hidden;
  margin: 0;
  padding: 0;
  font-family: 'Hanken Grotesk', sans-serif;
  font-size: 15px;
}
body{
  height: 100%;
  max-width: 100%;
  margin: 0;
  padding: 0;
}
#app{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  
  max-width: 100%;
}
h1{
 font-weight: 800;
 color: white;
}
h2{
  color: white;
  font-weight: 700;
}
h4{
 font-weight: 700;
 color: white;
}
p{
  font-weight: 500;
  color:var(--Light_lavender);
}
@media screen and (max-width:665px) {
  #app{
    display: flex;
    justify-content: flex-start;
  align-items: start;
  }
}
</style>
