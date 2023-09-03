<script>
import TheBrands from "./TheBrands.vue"
import TheOrganisations from "./TheOrganisations.vue"
export default {
    components: {
        TheBrands,
        TheOrganisations
    },
    data() {

},
mounted(){

}
}
</script>

<template>
    <section>
        <div class="container p-5">
            <div class="row pt-5 align-items-center">
                <div class="col">
                    <img src="../assets/svg/img1.svg" alt="img">
                </div>
                <div class="col-5">
                    <span>Business Growth</span>
                    <h1 class="title">Increase Brand Awareness</h1>
                    <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <button type="button" class="btn orangebg text-white mb-2 p-3" data-toggle="button" aria-pressed="false" autocomplete="off">
                                    Get A Consultation
                                </button>
                </div>                              
            </div>
        </div>
    </section>

    <section>
        <div class="container p-5">
            <div class="row flex-row-reverse pt-5 align-items-center">
                <div class="col d-flex justify-content-center">
                    <img src="../assets/svg/img2.svg" alt="img">
                </div>
                <div class="col-5">
                    <span>Investors In People</span>
                    <h1 class="title">In-House Sales Training</h1>
                    <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <button type="button" class="btn orangebg text-white mb-2 p-3" data-toggle="button" aria-pressed="false" autocomplete="off">
                                    Get A Consultation
                                </button>
                </div>                              
            </div>
        </div>
    </section>

    <section>
        <div class="container p-5 pb-5">
            <div class="row pt-5 align-items-center">
                <div class="col">
                    <img src="../assets/svg/img3.svg" alt="img">
                </div>
                <div class="col-5">
                    <span>Social Media Analysis</span>
                    <h1 class="title">Harness Your Social Proof</h1>
                    <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <button type="button" class="btn orangebg text-white mb-2 p-3" data-toggle="button" aria-pressed="false" autocomplete="off">
                                    Get A Consultation
                                </button>
                </div>                              
            </div>
        </div>
    </section>
    <TheBrands></TheBrands>
    <TheOrganisations></TheOrganisations>
    
</template>

<style lang="scss" scoped>
.container img {
    width: 80%;
    
}

.orangebg {
        background-color: #f86011;
    }

.title {
    font-size: 3rem;
}

.text {
font-size: 1.5rem;
}

</style>
