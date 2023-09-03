<script>
export default {
  
}
</script>

<template>
    <section class="pt-5">
        <div class="container pt-5">
    <div class="row d-flex gap-5">
        <div class="col-5">
            <h1>We Boost Our Clients’ Bottom Line by Optimizing Their Growth Potential. </h1>
        <h4 class="pb-4 pt-4">Quisque aliquet, libero consequat elementum convallis, erat risus imperdiet pellentesque sem neque eget.</h4>
        <button type="button" class="btn orangebg text-white p-3 ps-4 pe-4" 
            data-toggle="button" aria-pressed="false" autocomplete="off">
        <b>Why Work With Us</b>
    </button>
        </div>
        <div class="col text-end">
            <img class="rounded" src="../assets/images/we-boost-our-clients-600x549.jpg" alt="">
        </div>
    </div>
</div>
    </section>

</template>

<style lang="scss" scoped>
@import '../../partials/variables';


.col img {
    width: 90%;
}

h1 {
    font-size: 3.5rem;
}
.orangebg {
        background-color: $orange-site;
    }

section {
    background-color: $bg-grey;
}
</style>