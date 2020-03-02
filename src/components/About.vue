


<template>
  <div >
    <section class="section " id="about">
      
      <div class="container">
        <div class="section-heading">
          <h3 class="title is-2 has-text-black-bis sub-headings">Personal Info</h3>
        </div>
        <!-- <Services v-bind:skills="skillS" /> -->
        <!--sKILLS  -->
        <h3 class="title is-5 has-text-link sub-headings">Skills</h3>
        <div class="columns">
          <div v-for="(skill,index) in skills" v-bind:key="skill" class="column  has-text-black-ter kills">
            <strong class=" has-text-black-bis">{{index+1}}.{{skill.title}}:</strong> {{skill.details}}.
            
          </div>
          
        </div>
        <!-- EXPERIENCE Section -->
        <h3 class="title is-5 has-text-link sub-headings">Experience</h3>
        <div class="columns">
          
          <div v-for="(exp,index) in exps" v-bind:key="exp" class="column  kills">
            <p>
            <strong class=" has-text-black-bis">
              {{index+1}}.{{exp.title}}:
              </strong> 
              {{exp.role}}. 
              <small>
                ({{exp.timeSpan}}).
              </small>
              
            </p>
          </div>
        </div>

        <!-- VOLUNTEERING AND COMMUNITY SERVICES  -->
        <h3 class="title is-5 has-text-link  sub-headings">VOLUNTEERING AND COMMUNITY SERVICES</h3>
        <div class="columns">
          
          <div v-for="( work,index) in  voluntary" v-bind:key="work" class="column  kills">
            <p>
            <strong class=" has-text-black-bis">
              {{index+1}}.{{work.title}}:
              </strong> 
              {{work.role}}. >>>
              <small>
                ({{work.timeSpan}}).
              </small>
              
            </p>
          </div>
        </div>

      <!-- Award  -->
        <h3 class="title is-5 has-text-link sub-headings">AWARD</h3>
        <div class="columns">
          
          <div v-for="( award,index) in  award" v-bind:key="award" class="column kills">
            <p>
            <strong class=" has-text-black-bis">
              {{index+1}}.{{award.title}}:
              </strong> 
              {{award.role}}. >>>
              <small>
                ({{award.timeSpan}}).
              </small>
              
            </p>
          </div>
        </div>
        
        <a href="./assets/docs/resume.pdf" download target="_blank" class="button is-large is-link is-outlined">Download Resume <i class="material-icons">file_download</i></a>

      </div>
    </section>
  </div>
</template>

<script>
import Services from './Services';

export default {
  name: 'About',
  componenyt:{
    Services
  },
  props: {
    exps:Array,
    voluntary:Array,
    award:Array,
    skills:Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
