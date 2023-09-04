<script>
export default {
  
}
</script>

<template>
    <section class="pt-5 text-white">
        <div class="container pt-5">
    <div class="row d-flex gap-5 pb-5">
        <div class="col-6">
            <h1>Let’s Make Things Happen </h1>
            <h2 class="pb-4 pt-4">Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</h2>
            <hr>
            <h4 class="font-italic pb-4">“The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”</h4>
            <h5>George Anderson</h5>
            <span>Digitalbox CEO</span>
        </div>
        <div class="col">
            <div class="card p-3" style="width: 30rem;">
                    <div class="card-img text-center">
                        <img class="card-img-top" src="../assets/images/marketing-consultant-expert.jpg" alt="Card image cap">
                    </div>
                    
                    <div class="card-body text-center">
                        <h5 class="card-title" style="font-size: 1.5rem;">Richard Madsen</h5>
                        <p class="card-text pt-2" style="color:#848684; font-size: 1.2rem;">Marketing Consultant Expert</p>
                        <i class="fa-solid fa-phone pe-3 orange"></i>
                        <span class="orange"><b>(555) 802-1234</b></span>
                        <form>
                            <div class="row p-1 pt-4">
                                <input type="text" class="form-control mb-2 p-3" placeholder="Your Name*">
                                <input type="email" class="form-control mb-2 p-3" placeholder="Your Email*">
                                <input type="tel" class="form-control mb-2 p-3" placeholder="Your Phone Number*">
                                <button type="button" class="btn orangebg text-white mb-2 p-3" data-toggle="button" aria-pressed="false" autocomplete="off">
                                    Get A Callback
                                </button>
                                <span class="smalltext" style="color:#848684">By submitting my data I agree to be contacted</span>
                            </div>
                    </form>
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
    width: 15%;
    height: auto;
    border-radius: 50%;
}

h1 {
    font-size: 4rem;
}
.orangebg {
        background-color: $orange-site;
    }

section {
    background-color: #000;
}

.orange {
        color: $orange-site;
    }

</style>