<template>
  <div id="app" class="">
    <Navbar />
    <About />
    <Services v-bind:cert="certificate" v-bind:skills2="skill2" v-bind:skills="skill" v-bind:exps="experience" v-bind:exps2="experience2"  v-bind:award="awards"  />
    <Portfolio />
    <Contact v-bind:social="socials" />
    <Footer />
  </div>
</template>

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
          title:"Web Backend",
          details:"NodeJS (Adonis.js), Python (Flask)"
        },
        {
          title:"Sys Admin",
          details:"Systems Troubleshooting, Linux, Network integration"
        },
        {
          title:"Cloud",
          details:"Azure & GCP  "
        },
        {
          title:"Cloud Infrastructure",
          details:"Kubernetes, Rancher, Ansible"
        },
        {
          title:"Google Developer Group Ajah (GDG AJAH)",
          details:"Google IT Support Certification",
        },  
      ],
      skill2:[
      
       {
          title:"Data",
          details:"SQL, BigQuery for Data Analytics"
       }, {
          title:"Streaming",
          details:"Kafka, Hadoop, and GCP Cloud Dataflow"
       },
        {
          title:"Cloud",
          details:"GCP & Azure"
       }
      ],
      experience:[
        
        {
           title:"GDG Ajah (meet-up) ",
           role:"Organizer ",
           timeSpan:"February 2018 -  Present",
           link:"https://www.meetup.com/gdg-Ajah/"
        },
        {
           title:"Fullstack Developer Lagos Community (FSDLagos meet-up & Bootcamp) ",
           role:" Co-organizer",
           timeSpan:"February 2019 - Present",
           link:"https://fsdlagos.com.ng"
        },
        {
           title:"Lekki Trello Events",
           role:"Trello and Atlassian product user group - Co-organizer ",
           timeSpan:"Jan 2019 - Present ",
           link:" https://ace.atlassian.com/lekki-trello-events/"
        },{
           title:"TechGen Talent Lab",
           role:" A 14 weeks software development bootcamp. Training Facilitator ",
           timeSpan:"Sept 2019 - Dec 2019 "
        },
       
      ],
      experience2:[
        
        {
           title:"Unitech Global Resource NG,SA",
           role:"Telecomm support Engineer ",
           timeSpan:"August 2019 -  Present",
           link:"https://www.uniglobal.net/"
        },
        {
           title:"Uraban Aires ",
           role:"Digital Media Associate ",
           timeSpan:"JAN. 2018 - JUN. 2019 ",
           link:"http://urbane.ariesmoda.com"
        },

       
      ],
      awards:[
        {
          title:"NAIJAHACKS 2018 HACKATHON",
          role:"Winner",
          timeSpan:"OCT.2018"
        }
      ],
      certificate:[
        {
          title:"Google IT Supports Professional Certificate",
          role:"",
          timeSpan:"Jan 2020"
        }
      ],
      socials:[
        {
          email:"samokediji@gmail.com"
        },
        {
          medium:"https://medium.com/@Samuelokediji",
        },
        {
          Linkedin:"https://www.linkedin.com/in/okedijisamuelolaide/"
        },
        {
          Twitter:"https://twitter.com/SamuelOkediji_"
        },
        {
          Github:"https://github.com/Samuelokediji"
        }
       
      ],
    }
  }
}
</script>

<style>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css");
@import url("https://fonts.googleapis.com/icon?family=Material+Icons");
@import "https://cdn.jsdelivr.net/npm/bulma@0.8.0/css/bulma.min.css"; 
@import url('https://fonts.googleapis.com/css?family=Caveat|Oxanium|Spartan|Tajawal&display=swap');
@import url('https://fonts.googleapis.com/css?family=Rajdhani&display=swap');
html {
  scroll-behavior: smooth !important;
}
#app,button {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  font-family: 'Spartan', ;
  font-family: 'Oxanium', ;
  font-family: 'Caveat', ; */
  /* font-family: 'Tajawal', ; */
   font-family: 'Rajdhani';
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
p{
  font-size:20px;
}
.sub-headings{
  text-align:left !important;
  /* font-family: 'Spartan' ; */
  font-family: 'Oxanium' !important;
  /* font-family: 'Caveat' !important;  */
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
  margin-bottom: 3em;
  border-top:1px solid #333;  
}

</style>
