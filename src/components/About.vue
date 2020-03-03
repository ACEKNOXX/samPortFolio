<template>
    <div>
      <section class="section has-background-black-bis " id="services">
        
        <div class="container">
          <div class="section-heading">
            <h3 class="title is-2 has-text-grey-lighter sub-headings">About Me</h3>
          </div>
          <div class="section-body-foot">
            <div class="columns">             
              <article class="column is-full has-text-grey-lighter">
                
                <p>
                  Hi I'm <span class=" has-text-danger">Samuel Okediji.</span> A software engineer 
                  based in Lagos. I am a seasoned and experience web developer, who has made differences with my 
                  expertise at writing frontend applications with intermediate proficiency in React and also 
                  developing and managing backend applications with NodeJS (AdonisJS), Python (Flask). I also double as a DevOps 
                  Engineer with a lot of fancy for GCP, and 4 years experience working with Microsoft Azure.</p>
                <p>
                  Off work, I am mostly called a man with a heart for people. I engage 
                  in  various volunteering and community programs. It's either you remember 
                  me from my time in organizing and leading meetups or  workshop classes on 
                  the platform of GDG Ajah. I also volunteer in organizing 
                  Bootcamps and meetups with  FSD Lagos  (Fullstack Developers Lagos) Community.
                </p>
              </article>
              
            </div>
            
          </div>

        </div>
      </section>
    </div>
</template>
<script>
export default {
    name:'About',
    props:{
      skills:Array
    }
}
</script>
<style scoped>
</style>
