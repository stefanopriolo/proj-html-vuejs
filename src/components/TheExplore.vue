<script>
export default {
  
}
</script>

<template>
    <section class="pt-5">
        <div class="container pt-5">
            <div class="row pb-5">
                <div class="col-6">
                    <h1>Marketing Resources: Insider Advice on How to Increase Online Sales</h1>
                </div>
                <div class="col d-flex flex-column justify-content-end align-items-end">
                        <button type="button" class="btn orangebg text-white p-3 ps-4 pe-4" 
                        data-toggle="button" aria-pressed="false" autocomplete="off">
                        <b>Explore All Resources</b>
                    </button>      
                </div>            
            </div>
            <div class="row gap-4 pt-5">
                <div class="col">
                    <img class="pb-4" src="../assets/images/blog-posts-6-1200x800.jpg" alt="">
                    <h2>Marketing Tips And Tricks For Your Website</h2>
                </div>

                <div class="col">
                    <img class="pb-4" src="../assets/images/blog-posts-5-1200x800.jpg" alt="">
                    <h2>How to Write Stunning Blog Post Titles</h2>
                </div>

                <div class="col">
                    <img class="pb-4" src="../assets/images/blog-posts-4-1200x800.jpg" alt="">
                    <h2>Techniques to Reduce Facebook Ads Spend</h2>
                </div>

                
                
                </div>
              
            </div>

    </section>

</template>

<style lang="scss" scoped>
@import '../../partials/variables';

section {
    background-color: $bg-grey;
}

.orangebg {
        background-color: $orange-site;
    }

    h1 {
    font-size: 3.4rem;
}

img {
    width: 100%;
}
</style>