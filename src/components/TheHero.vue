<script>
</script>

<template>
    <section class="pt-5">
        <div class="container d-flex text-white pt-5">
            <div class="row pt-5">
                <div class="col-7 pt-5">
                    <h1 class="display-1"><b>Unlock Your Online Growth Potential</b></h1>
                <h2>Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</h2>
                <button type="button" class="btn btn-outline-dark p-3 mt-3">Our Services <i class=" arrow-icon fa-solid fa-arrow-right" style="color: #000000;"></i></button>
                </div>
                <div class="col-5 pt-5">
                    <div class="card card-xl position-absolute p-3">
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

section {
    background-image: url(../assets/images/marketing-intro.jpg);
    background-size: cover;
    height: 720px;


    img {
        width: 70px;
        border-radius: 50%;
    }

    .orange {
        color: $orange-site;
    }
    
    .orangebg {
        background-color: $orange-site;
    }

    .smalltext {
        font-size: 0.7rem;
    }

    .card-xl {
    width: 400px; 
    height: auto; 
}

.btn-outline-dark {
    background-color: #fff; 
    color: #000; 
    border-color: #000;
    transition: background-color 0.3s, color 0.3s; 
  }

  .btn-outline-dark:hover {
    background-color: transparent; 
    color: #fff; 
    border-color: #fff;
  }

  .btn-outline-dark:hover .arrow-icon {
    color: #fff; 
  }
}
</style>
