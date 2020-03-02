<template>
  <div id="app" class="has-background-black-ter">
    <Navbar />
    <Services v-bind:skills="skill" />
    <About />
    <Portfolio />
    <Contact />
    <Footer />
  </div>
</template>

<script src="https://kit.fontawesome.com/yourcode.js"></script>
<script>
import Navbar from './components/Navbar'
import About from './components/About'
import Portfolio from './components/portfolio';
import Footer from './components/Footer';
import Services from './components/Services';
import Contact from './components/Contact';

export default {
  name: 'App',
  components: {
    Navbar,About,Portfolio,Footer,Services,Contact
  },data(){
    return {
      skill:[
        {
          title:"Web Frontend",
          details:"Html/Css/JS/ReactJS"
        },
        {
          title:"Web ",
          details:"Html/Css/JS"
        }
      ]
    }
  }
}
</script>

<style>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css");
@import url("https://fonts.googleapis.com/icon?family=Material+Icons");
@import "https://cdn.jsdelivr.net/npm/bulma@0.8.0/css/bulma.min.css"; 
@import url('https://fonts.googleapis.com/css?family=Caveat|Oxanium|Spartan|Tajawal&display=swap');
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  font-family: 'Spartan', ;
  font-family: 'Oxanium', ;
  font-family: 'Caveat', ; */
  font-family: 'Tajawal', ;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
 
  /* color: #2c3e50; */
  /* margin-top: 60px;. */
}
h1{
font-family: 'Spartan' ;
  /* font-family: 'Oxanium', ; */
  /* font-family: 'Caveat', ;  */
}
.sub-headings{
  text-align:left !important;
}
.has-same-height .card {
  height: 320px;
  overflow: hidden;
}

.card-content h3 {
  text-align: center;
}

.table-profile td,
th {
  border: none !important;
}

.table-profile td:first-of-type {
  font-weight: bold;
}

.skills-content .media {
  margin: 0 !important;
  padding: 4px !important;
  border: 0 !important;
}

.skills-content .progress {
  height: 4px !important;
}



.portfolio-container .card {
  margin-bottom: 2em;
}

.section-heading {
  text-align: center;
  margin-top: 1em;
  margin-bottom: 6em;
  border-top:1px solid rgb(43, 39, 39);  
}

</style>
