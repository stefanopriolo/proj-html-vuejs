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
            <div class="image-container">
                <img class="card-img-top" src="../assets/images/case-studies-1-1200x1349.jpg" alt="Card image cap">
                <div class="overlay"></div>
            </div>
        <h3 class="mt-4"><a class="text-decoration-none text-black" href="">How Spaces attracted five million visitors by improving the content</a></h3>
        <hr class="dashed w-100 mx-auto">
        <span><b>200%</b></span>
        <h5>Higher revenue from digital</h5>
        </div>
    </div>

    <div class="row pt-5">
        <div class="card" style="width: 25rem;">
            <div class="image-container">
                <img class="card-img-top" src="../assets/images/case-studies-4-1200x1349.jpg" alt="Card image cap">
                <div class="overlay"></div>
            </div>
            <h3 class="mt-4"><a class="text-decoration-none text-black" href="">Creativity helped Hemisferio to increase their brand reach vertically</a></h3>
        <hr class="dashed w-100 mx-auto">
        <span><b>10x</b></span>
        <h5>Sales increase with the same ad spend</h5>
        </div>
    </div>

    <div class="row pt-5">
        <div class="card" style="width: 25rem;">
            <div class="image-container">
                <img class="card-img-top" src="../assets/images/case-studies-6-1200x1349.jpg" alt="Card image cap">
                <div class="overlay"></div>
            </div>
            <h3 class="mt-4"><a class="text-decoration-none text-black" href="">How DigitalBox used AI-powered data insight to boost sales</a></h3>
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

  .image-container {
    position: relative; /* Posizionare correttamente l'overlay */
  }

  .card-img-top {
    width: 100%;
    height: auto;
    display: block;
    transition: transform 0.5s;
    z-index: 1; /* Assicura che l'immagine sia sopra l'overlay */
  }

  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to bottom, transparent, $orange-site); /* Gradiente arancione */
    opacity: 0;
    transition: opacity 2s;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 2; /* Posiziona l'overlay sopra l'immagine */
  }

  .overlay i {
    font-size: 40px;
    color: #fff;
  }

  .image-container:hover .overlay {
    opacity: 1; /* Sovrapposizione visibile all'hover solo sull'immagine */
  }

  .hover-orange {
    color: $orange-site; /* Colore arancione all'hover */
  }
</style>