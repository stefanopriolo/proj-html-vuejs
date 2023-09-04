<script>
</script>

<template>
    <nav class="navbar d-flex justify-content-center navbar-expand-lg navbar-light bg-light p-4 gap-3">
      <img class="pe-5" src="../assets/images/avada-marketing-logo.png" alt="logo">  
    <a class="navbar-brand" href="#">Home<i class="fa-solid fa-angle-down align-middle ps-1" style="color: #000000;"></i></a>   
    <a class="navbar-brand" href="#">Services<i class="fa-solid fa-angle-down align-middle ps-1" style="color: #000000;"></i></a>
  <a class="navbar-brand" href="#">Why Us</a>
  <a class="navbar-brand" href="#">Case Studies</a>
  <a class="navbar-brand" href="#">About</a>
  <a class="navbar-brand" href="#">Blog</a>
  <a class="navbar-brand ps-5" href="#"><i class="fa-solid fa-phone pe-3" style="color: #f86011;"></i>(555) 802-1234</a>
  <form class="form-inline my-2 my-lg-0">
      <button class="btn btn-outline my-2 my-sm-0 btn-lg orange" type="submit">Free Quote</button>
    </form>
</nav>
</template>

<style lang="scss" scoped>
@import '../../partials/variables';
.navbar {
  z-index: 1000;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  right: 0;
}

.orange {
  color: $orange-site;
  background-color: #f862112f;
}

.navbar-brand {
  color: #000000;
  position: relative;
  transition: color 0.2s; 
}

.btn.orange:hover {
  background-color: $orange-site; 
  color: white;
  transition: background-color 0.3s, color 0.3s; 
}

.navbar-brand:hover {
  color: $orange-site; 
}

.navbar-brand:hover:after {
  width: 100%;
  opacity: 1;
}

.navbar-brand::after {
  content: ""; 
  display: block; 
  height: 3px; 
  width: 0; 
  background-color: $orange-site; 
  position: absolute; 
  bottom: -3px;
  left: 50%; 
  transform: translateX(-50%); 
  transition: width 0.2s, opacity 0.3s; 
  opacity: 0; 
  transform-origin: center bottom;
}

/* Stile specifico per il numero di telefono senza effetto di hover */
.navbar-brand:last-child:hover::after {
  width: 0;
  opacity: 0;
}
</style>
