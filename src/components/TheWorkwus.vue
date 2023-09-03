<script>
export default {
  
}
</script>

<template>
    <section class="pt-5">
        <div class="container pt-5">
    <div class="row d-flex gap-5 pb-5">
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
    <div class="row d-flex gap-5 pt-5">
        <div class="col-5">
            <h2 class="pb-3">We Build Relationships </h2>
        <h5 class="pb-5">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</h5>

        <h2 class="pb-3">Proprietary Processes </h2>
        <h5 class="pb-5">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</h5>
    
        </div>
        <div class="col ps-5">
            <div class="icon-container d-flex align-items-center gap-2 pb-5">
                <img id="icon" src="../assets/image (2).png" alt="">
                <div class="icon-texts">
                    <h4 class="pb-3">Accountability</h4>
                    <h5>Curabitur ac leo nunc vestibulum</h5>
                </div>
            </div>
           
            <div class="icon-container d-flex align-items-center gap-2 pb-5">
                <img id="icon" src="../assets/image (3).png" alt="">
                <div class="icon-texts">
                    <h4 class="pb-3">Transparency</h4>
                    <h5>Curabitur ac leo nunc vestibulum</h5>
                </div>
            </div>

            <div class="icon-container d-flex align-items-center gap-2 pb-5">
                <img id="icon" src="../assets/image (4).png" alt="">
                <div class="icon-texts">
                    <h4 class="pb-3">Investment</h4>
                    <h5>Curabitur ac leo nunc vestibulum</h5>
                </div>
            </div>
        </div>
    </div>

</div>
    </section>

</template>

<style lang="scss" scoped>
@import '../../partials/variables';


#icon {
    width: 6rem;
}

.col img {
    width: 90%;
    height: auto;
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