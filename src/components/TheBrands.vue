<script>
export default {

}
</script>

<template>
<section>
    <div class="container pt-5">
        <div class="row d-flex justify-content-center text-center gap-2 pb-5">
            <h1>Some Brands We Work With</h1>
            <p class="pb-4">Quisque aliquet, libero consequat elementum convallis.</p>
            <img src="../assets/images/abstract.png" alt="">
            <img src="../assets/images/cglobal.png" alt="">
            <img src="../assets/images/next.png" alt="">
            <img src="../assets/images/hemisferio.png" alt="">
            <img src="../assets/images/spaces.png" alt="">
            <img src="../assets/images/digitalbox.png" alt="">
        </div>
       <!-- Card ragazza con numero -->
        <div class="row p-4 pt-5">
    <div class="card mb-5 p-3 d-flex flex-row align-items-center justify-content-around">
        <div class="user d-flex align-items-center gap-3">
        <img class="icon" src="../assets/images/marketing-expert-cta.png" alt="">
            <div class="usertext">
                <h4>Sandy Reiff</h4>
                <span>Marketing Consultant Expert</span>
            </div>
            
    </div>          
     <p>Drive Leads and Sales with Avada</p>
    <form class="form-inline my-2 my-lg-0">
        <button class="btn btn-outline-success my-2 my-sm-0 btn-lg" type="submit"><span class="orange"><b><i class="fa-solid fa-phone pe-3 orange"></i>(555) 802-1234</b></span></button>
    </form>
    </div>
    
</div>
   </div>

</section>

</template>

<style lang="scss" scoped>
.container img:not(.icon) {
    width: 15%;
    
}

.icon {
    width: 20%;
    border-radius: 50%;
    display: inline-block;
}

.card {
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
}
.title {
    font-size: 3rem;
}

.text {
font-size: 1.5rem;
}

.orange {
        color: #f86011;
    }

p {
    font-size: 1.5rem;
}

h1 {
    font-size: 3rem;
}
</style>
