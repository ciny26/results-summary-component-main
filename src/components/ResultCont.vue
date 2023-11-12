<template>
    <div class="cont cont1">
        <h4>Your Result</h4>
        <div class="result_comp">
            <h1>76</h1>
            <p>of 100</p>
        </div>
        <div class="result_desc">
            <h2 class="result_note">
                Great
            </h2>
            <p class="desc">
                You Scored more than
                65% of the people who have taken
                taken these tests. 
            </p>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .cont{
        display: flex;
        align-items: center;
        flex-direction: column;
        padding: 1rem;
    }
    .cont > * {
        text-align: center;
        flex: 1;
    }
    .cont1{
        background: linear-gradient(to top ,var(--royal_blue),var(--violet_blue ) , var(--light_slate_blue));
    }
    .result_comp{
        width: 120px;
        height: 120px;
        border-radius: 50%;
        background-color: var(--violet_blue);
    }
    
</style>