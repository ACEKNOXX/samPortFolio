<template>
  <div >
    <!-- Navigation bar -->
  <nav class="navbar has-background-black-bis  is-fixed-top">
    <div class="navbar-brand">
      <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <div id="navbarExampleTransparentExample" class="navbar-menu">
      <div class="navbar-end">
        <a class="navbar-item" href="#about">
          <span class="icon">
            <i class="fas fa-info"></i>
          </span>
          <span>About</span>
        </a>
        <a class="navbar-item" href="#services">
          <span class="icon">
            <i class="fas fa-bars"></i>
          </span>
          <span>Services</span>
        </a>
        <a class="navbar-item" href="#resume">
          <span class="icon">
            <i class="fas fa-file-alt"></i>
          </span>
          <span>Resume</span>
        </a>
        <a class="navbar-item" href="#portfolio">
          <span class="icon">
            <i class="fas fa-th-list"></i>
          </span>
          <span>Portfolio</span>
        </a>
        <a class="navbar-item" href="#contact">
          <span class="icon">
            <i class="fas fa-envelope"></i>
          </span>
          <span>Contact</span>
        </a>
      </div>
    </div>
  </nav>

  <!-- Header -->
  <section class="hero has-background-black-bis is-fullheight is-fullheight-with-navbar">
    <div class="hero-body">
      <div class="container has-text-grey-lighter">
          <div class="round-head-shot"></div>
          <!-- <img src="../assets/logo.png" alt=""> -->
          <h6 class="subtitle is-6 has-text-grey-lighter ">Hello! I am</h6>
        <h1 class="title is-1 has-text-danger">
          Samuel Okediji 
        </h1>
        <h2 class="subtitle is-3 has-text-grey-lighter ">
          Full Stack Software Engineer
        </h2>
        <br><br><br><br>
        <div class="colums">
            <h6>
                <a href="#portfolio" class="has-text-primary">
                See my works...
                    <span class="icon"><br>
                        <i class="material-icons small">trending_flat</i>
                    </span>
                </a>
            </h6>
            
            <!-- <img src="../assets/undraw_researching.svg" width="250px" height="250px" alt="PLay image"> -->
        </div>
      </div>
      
    </div>
  </section>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
   
  }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Caveat|Oxanium|Spartan|Tajawal&display=swap');
@import url('https://fonts.googleapis.com/css?family=Monoton&display=swap');
.title{
   /* font-family: Avenir, Helvetica, Arial, sans-serif;
  font-family: 'Spartan', ;
  font-family: 'Oxanium', ; */
  /* font-family: 'Caveat' !important  ; */
  /* font-family: 'Tajawal' ; */
  font-family: 'Monoton' ;
}
.round-head-shot{
  width:300px;
  height:300px;
  border-radius:100%;
  background: url("../assets/sam.jpeg");
  background-repeat: no-repeat;
  background-size:cover;
  background-position:left center;
  border:9px solid  #333;
}
</style>
