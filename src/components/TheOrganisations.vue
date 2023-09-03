<script>
export default {

}
</script>


<template>
     <h1 class="text-center pt-4 pb-3">Trusted by Leading Organisations</h1>
<div class="container d-flex gap-5 justify-content-center">
       
    <!-- Cards: -->
    <div class="row pt-5">
        <div class="card" style="width: 25rem;">
            <img class="card-img-top" src="../assets/images/case-studies-1-1200x1349.jpg" alt="Card image cap">
            <h3 class="mt-4">How Spaces attracted five million visitors by improving the content</h3>
            <hr class="dashed w-100 mx-auto">
            <span><b>200%</b></span>
            <h5>Higher revenue from digital</h5>
        </div>
    </div>

    <div class="row pt-5">
        <div class="card" style="width: 25rem;">
            <img class="card-img-top" src="../assets/images/case-studies-4-1200x1349.jpg" alt="Card image cap">
            <h3 class="mt-4">Creativity helped Hemisferio to increase their brand reach vertically</h3>
            <hr class="dashed w-100 mx-auto">
            <span><b>10x</b></span>
            <h5>Sales increase with the same ad spend</h5>
        </div>
    </div>

    <div class="row pt-5">
        <div class="card" style="width: 25rem;">
            <img class="card-img-top" src="../assets/images/case-studies-6-1200x1349.jpg" alt="Card image cap">
            <h3 class="mt-4">How DigitalBox used AI-powered data insight to boost sales</h3>
            <hr class="dashed w-100 mx-auto">
            <span><b>3-year</b></span>
            <h5>Partnership with Avada Consultant</h5>
        </div>
    </div>
</div>
<div class="text-center pt-5 pb-5 mb-5">
    <button type="button" class="btn orangebg text-white p-2 ps-4 pe-4" 
            data-toggle="button" aria-pressed="false" autocomplete="off">
        <b>Read More Case Studies</b>
    </button>
</div>
</template>


<style scoped lang="scss"> 
@import '../../partials/variables';

span {
    font-size: 4rem;
}

.card {
    border: none;
}

hr.dashed {
    border: none;
    border-top: 1px dashed #4444449a;
    width: 50%;
}
.orangebg {
        background-color: $orange-site;
    }
</style>