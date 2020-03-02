<template>
  <div >
    <!-- Navigation bar -->
  <nav class="navbar   is-fixed-top">
    <div class="navbar-brand">
      <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <!-- <div id="navbarExampleTransparentExample" class="navbar-menu">
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
    </div> -->
  </nav>

  <!-- Header -->
  <section class="hero  is-fullheight is-fullheight-with-navbar">
    <div class="hero-body">
      <div class="container has-text-grey-lighter">
        <br>
        <div class="columns">

          <div class="column">
            <div class="round-head-shot"></div>
            <!-- <div class="is-full columns">
              <a href="#" class=""> <i class="fab fa-medium fa-2x"></i> </a>
              <a href="#"> <i class="fab fa-twitter"></i> </a>
              <a href="#"> <i class="fab fa-github-alt"></i> </a>
              <a href="#"> <i class="fab fa-linkedin-in"></i> </a>
            </div> -->
          </div>
          <div class="column left">
              <h6 class="subtitle is-6 has-text-black-ter ">Hello! I am</h6>
              <h1 class="title is-1 has-text-ter">
              Samuel Okediji 
              </h1>
              <h2 class="subtitle is-3 has-text-black-bis">
              Software Engineer
              </h2>
              <h4 class="subtitle is-6 has-text-black-bis">
                <i class="material-icons medium has-text-danger">location_on</i>Lagos,Nigeria
              </h4>
              <br><br><br><br>
              <div class="">
                <h6>
                    <a href="#portfolio" class="has-text-link">
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
  border:9px solid  #eee;
}
.left{
  text-align:right !important;
}
</style>
