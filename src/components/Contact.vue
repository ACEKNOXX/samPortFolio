<template>
    <div>
        <section class="section has-background-black-bis" id="contact">
            <div class="container">
                <div class="section-heading">
                    <h3 class="title is-2 has-text-grey-lighter sub-headings">Contact</h3>
                </div>
                
                <div class="columns">
                    <!-- <div class="column "> -->
                        <div class="column  has-text-light ">
                            <a v-bind:href="social.email" class="has-text-danger"> <i class="fas fa-envelope fa-2x"></i>@ Samokediji@gmail.com</a>
                        </div>
                        <div class="column  has-text-light ">
                            <a v-bind:href="social.medium" class="has-text-success "> <i class="fab fa-medium fa-2x"></i> @Samuelokediji</a>
                        </div>
                        <div class="column has-text-light ">
                            <a v-bind:href="social.Twiitter" class="has-text-link   "> <i class="fab fa-twitter-square fa-2x"></i> @SamuelOkediji</a>
                        </div>
                        <div class="column has-text-light ">
                            <a v-bind:href="social.Github" class="has-text-black-ter has-text-grey-lighter  "> <i class="fab fa-github-square fa-2x"></i> @Samuelokediji </a>
                        </div>
                        <div class="column has-text-light ">
                            <a v-bind:href="social.Linkedin" class="has-text-link "> <i class="fab fa-linkedin-in fa-2x"></i> @okedijisamuelolaide</a>
                        </div>
                    <!-- </div> -->
                        <!-- <div class=" column is-three-fifths section-bodying"> -->
                            <!-- <div class="field">
                                <label class="label has-text-grey-lighter ">Name</label>
                                <div class="control">
                                    <input class="input" type="text" placeholder="Text input">
                                </div>
                            </div> -->

                            <!-- <div class="field">
                                <label class="label has-text-grey-lighter">Subject</label>
                                <div class="control">
                                    <input class="input" type="text" placeholder="Subject">
                                </div>
                            </div> -->
    

                            <!-- <div class="field">
                            <label class="label has-text-grey-lighter">Email</label>
                            <div class="control has-icons-left has-icons-right">
                                <input class="input " type="email" placeholder="Email" value="hello@">
                                <span class="icon is-small is-left">
                                <i class="fas fa-envelope"></i>
                                </span>
                                
                            </div> 
                            
                            </div>-->

                          

                            <!-- <div class="field">
                                <label class="label has-text-grey-lighter">Message</label>
                                <div class="control">
                                    <textarea class="textarea" placeholder="Message"></textarea>
                                </div>
                            </div> -->

                            <!-- <div class="field is-grouped">
                            <div class="control">
                                <button class="button is-primary is-outlined is-medium">Send Message</button>
                            </div>
                            
                            </div> -->
                    <!-- </div> -->
                </div>
            </div>
        </section>
    </div>
</template>
<script>
export default {
    name:'Contact',
    props:{
        social:Array
    }
}
</script>
<style scoped>

</style>