<template>
    <div>
        <section class="section " id="contact">
            <div class="container">
                <div class="section-heading">
                    <h3 class="title is-2 has-text-black-bis sub-headings">Contact</h3>
                </div>
                
                <div class="columns">
                    <div class="column ">
                        <div class="column  has-text-light ">
                            <a href="#" class="has-text-success "> <i class="fab fa-medium fa-2x"></i> @Sam okediji</a>
                        </div>
                        <div class="column has-text-light ">
                            <a href="#" class="has-text-link   "> <i class="fab fa-twitter-square fa-2x"></i>  @Sam okediji</a>
                        </div>
                        <div class="column has-text-light ">
                            <a href="#" class="has-text-black-ter  "> <i class="fab fa-github-square fa-2x"></i> @sam okediji </a>
                        </div>
                        <div class="column has-text-light ">
                            <a href="#" class="has-text-link "> <i class="fab fa-linkedin-in fa-2x"></i> @Sam okediji </a>
                        </div>
                    </div>
                
                
                
                        <div class=" column is-three-fifths section-bodying">
                            <div class="field">
                                <label class="label  ">Name</label>
                                <div class="control">
                                    <input class="input" type="text" placeholder="Text input">
                                </div>
                            </div>

                            <div class="field">
                                <label class="label ">Subject</label>
                                <div class="control">
                                    <input class="input" type="text" placeholder="Subject">
                                </div>
                            </div>
    

                            <div class="field">
                            <label class="label">Email</label>
                            <div class="control has-icons-left has-icons-right">
                                <input class="input " type="email" placeholder="Email" value="hello@">
                                <span class="icon is-small is-left">
                                <i class="fas fa-envelope"></i>
                                </span>
                                
                            </div>
                            
                            </div>

                          

                            <div class="field">
                                <label class="label">Message</label>
                                <div class="control">
                                    <textarea class="textarea" placeholder="Message"></textarea>
                                </div>
                            </div>

                            <div class="field is-grouped">
                            <div class="control">
                                <button class="button is-link is-outlined is-medium">Send Message</button>
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
    name:'Contact'
}
</script>
<style scoped>

</style>