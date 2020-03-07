<template>
  <div >
    <section class="section has-background-black-bis" id="about">
      
      <div class="container">
        <div class="section-heading">
          <h3 class="title is-2 has-text-grey-lighter sub-headings">Personal Info</h3>
        </div>
        <!-- <Services v-bind:skills="skillS" /> -->
        <!--sKILLS  -->
        <h3 class="title is-5 has-text-grey-lighter sub-headings">Skills</h3>
        <div class="columns">
          <div v-for="(skill,index) in skills" v-bind:key="skill" class="column  has-text-grey-lighter kills">
            <p>
            
            <strong class=" has-text-danger">{{index+1}}.{{skill.title}}:</strong> {{skill.details}}.
              
            </p>
          </div>
          
        </div>
        <div class="columns">
          <div v-for="(skill,index) in skills2" v-bind:key="skill" class="column  has-text-grey-lighter kills">
            <p>
            
            <strong class=" has-text-danger">{{index+6}}.{{skill.title}}:</strong> {{skill.details}}.
              
            </p>
          </div>
          
        </div>
        <!-- EXPERIENCE Section -->
        <h3 class="title is-5 has-text-grey-lighter sub-headings">Experience</h3>
        <div class="columns">
          
          <div v-for="(exp,index) in exps" v-bind:key="exp" class="column has-text-grey-lighter  kills">
            <p>
            <strong class=" has-text-danger">
              {{index+1}}.{{exp.title}}:
              </strong> 
              {{exp.role}}. 
              <small>
                ({{exp.timeSpan}}).
              </small>
               <a v-if="exp.link" class="has-text-primary" v-bind:href="exp.link">Ckeck</a>
            </p>
          </div>
        </div>
        
        <!-- Certifications -->
        <h3 class="title is-5 has-text-grey-lighter sub-headings">CERTIFICATION</h3>
        <div class="columns">
          <div v-for="(cer,index) in cert" v-bind:key="cer" class="column has-text-grey-lighter  kills">
            <p>
            <strong class=" has-text-danger">
              {{index+1}}.{{cer.title}}:
              </strong> 
              {{cer.role}}. 
              <small>
                ({{cer.timeSpan}}).
              </small>
               <a v-if="cer.link" class="has-text-primary" v-bind:href="cer.link">Check</a>
            </p>
          </div>
        </div>

      <!-- Award  -->
        <h3 class="title is-5 has-text-grey-lighter sub-headings">AWARD</h3>
        <div class="columns">
          
          <div v-for="( award,index) in  award" v-bind:key="award" class="column has-text-grey-lighter kills">
            <p>
            <strong class=" has-text-danger ">
              {{index+1}}.{{award.title}}:
              </strong> 
              {{award.role}}. >>>
              <small>
                ({{award.timeSpan}}).
              </small>
             
            </p>
          </div>
        </div>
        
        
        <a href="./assets/docs/resume.pdf" download target="_blank" class="button is-medium is-danger is-outlined">Download Resume <i class="material-icons">file_download</i></a>

      </div>
    </section>
  </div>
</template>

<script>
import Services from './Services';

export default {
  name: 'Services',
  componenyt:{
    Services
  },
  props: {
    exps:Array,
    cert:Array,
    award:Array,
    skills:Array,
    skills2:Array

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
