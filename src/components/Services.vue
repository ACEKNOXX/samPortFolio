<template>
    <div>
      <section class="section has-background-black-bis" id="services">
        
        <div class="container">
          <div class="section-heading">
            <h3 class="title is-2 has-text-grey-lighter sub-headings">Skills</h3>
          </div>
          <div class="section-body-foot">
            <li class="has-text-grey-lighter " v-for="(skill,index) in skills" v-bind:key="skill">
              {{index+1}}.{{skill.title}}
            </li>
            <a href="./assets/docs/resume.pdf" download target="_blank" class="button is-large is-danger is-outlined">Download Resume <i class="material-icons">file_download</i></a>
          </div>

        </div>
      </section>
    </div>
</template>
<script>
export default {
    name:'Services',
    props:{
      skills:Array
    }
}
</script>
<style scoped>

</style>