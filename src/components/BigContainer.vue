<template>
    <div class="container">
      <result-cont></result-cont>
      <summary-comp></summary-comp> 
    </div>
</template>
<script>
import ResultCont from './ResultCont.vue';
import SummaryComp from './SummaryComp.vue';
export default {
    components:{
        ResultCont,
        SummaryComp
    }
}
</script>
<style>
    .container{
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        
        height: fit-content;
        margin: auto;
        border-radius: 2rem;
        border: 0.5px solid var(--Light_lavender);
        box-shadow: 10px 10px 38px 0px rgba(0,0,0,0.75);
        
    }
    .container > *{
        flex: 1;
    }
    @media screen and (max-width:665px) {
        .container{
            flex-direction: column;
            width: 100%;
            height: 100%;
            border-radius: 0;
        }
        .cont1{
            max-height: 250px;
            margin: 0;
            height: 25%;
            width: 100%;
            padding: 3px 0 0 0 ;
            justify-content: center;
            border-radius: 0 0 30px 30px;
        }
        .cont1>*{
            margin: 0;
            flex: 1;
        }
        .cont2{
            justify-content: flex-start;
            margin: 0;
            height: 75%;
        }
        
        .cont2>h4{
            flex: 0;
            margin: 0 0 4px 0;
        }
        .continue_btn{
            margin: 0 auto;
            max-height: 45px;
            background-color: var(--Dark_gray_blue);
        }
    }
</style>