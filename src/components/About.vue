<template>
  <div >
    <section class="section has-background-black-bis" id="about">
      
      <div class="container">
        <div class="section-heading">
          <h3 class="title is-2 has-text-grey-lighter sub-headings">Personal Info</h3>
        </div>
        <!-- EXPERIENCE Section -->
        <h3 class="title is-5 has-text-grey-lighter sub-headings">Experience</h3>
        <div class="columns">
          
          <div v-for="(exp,index) in exps" v-bind:key="exp" class="column has-text-grey-lighter kills">
            <p>
            <strong class=" has-text-danger">
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
        <h3 class="title is-5 has-text-grey-lighter sub-headings">VOLUNTEERING AND COMMUNITY SERVICES</h3>
        <div class="columns">
          
          <div v-for="( work,index) in  voluntary" v-bind:key="work" class="column has-text-grey-lighter kills">
            <p>
            <strong class=" has-text-danger">
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
        <h3 class="title is-5 has-text-grey-lighter sub-headings">AWARD</h3>
        <div class="columns">
          
          <div v-for="( award,index) in  award" v-bind:key="award" class="column has-text-grey-lighter kills">
            <p>
            <strong class=" has-text-danger">
              {{index+1}}.{{award.title}}:
              </strong> 
              {{award.role}}. >>>
              <small>
                ({{award.timeSpan}}).
              </small>
              
            </p>
          </div>
        </div>

      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'About',
  props: {
    exps:Array,
    voluntary:Array,
    award:Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
