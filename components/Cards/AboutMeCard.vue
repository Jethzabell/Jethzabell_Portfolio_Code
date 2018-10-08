<template>
    <section id="about-me">
        <b-container class="wOutShadow">
            <b-row>
                <b-col md="8">
                    <h2 style="margin-top:2rem;color: rgb(63, 63, 63);">About Me</h2>
                </b-col>
            </b-row>
            <b-row>
                <b-col lg="4" style="margin-bottom:5rem;margin-top:2.5rem;">
                    <b-list-group>
                        <b-list-group-item class="group"><span class="theItemSpaceL">Location:</span><span class="theItemSpace">Durham, North Carolina</span></b-list-group-item>
                        <b-list-group-item class="group"><span class="theItemSpaceL">Email:</span><span class="theItemSpace">jethzabell.medina@gmail.com</span></b-list-group-item>
                        <b-list-group-item class="group"><span class="theItemSpaceL">Phone:</span><span class="theItemSpace">+1 787 420 7746</span></b-list-group-item>
                        <b-list-group-item class="group"><span class="theItemSpaceL">Bilingual:</span><span class="theItemSpace">Spanish and English</span></b-list-group-item>
                    </b-list-group>
                     <b-button class="buttonMargin" size="md" href="https://drive.google.com/file/d/1RZCQXQ5BeiSLvhz4WvQFQes2W-1AWdhx/view?usp=sharing">Download my Resume</b-button>
                </b-col>
                <b-col lg="8" style="color: rgb(63, 63, 63);">
                    <h4 style="margin-top:2.5rem;">Hi,</h4>
                    <p>
                        I am Jethzabell, a young profesional with experience in Software Development. Currently I work in IBM as a Software Enginieer.    
                        BS in Computer Science(2015). Currently applying for a MD in Computer Science(2021). 
                        My main programming language is C++, but now I work more with Web Development.
                    </p>

                    <p>I spend most of my spare time coding, playing basketball, and traveling around the world.</p>
                            
                    
                    
                    <ul class="list-inline">
                        <li class="list-inline-item">
                            <a href="https://www.linkedin.com/in/jethzabell-medina/"><b-img src="/linkedIn.png"/></a>
                        </li>
                        <li class="list-inline-item">
                            <a href="https://github.com/Jethzabell"><b-img src="/github.png"/></a>
                        </li>
                         <li class="list-inline-item">
                            <a href="https://medium.com/vue-mastery/10-reasons-to-use-nuxt-js-for-your-next-web-application-522397c9366b"><b-img src="/nuxt.png"/></a>
                        </li>
                    </ul>
                </b-col>
            </b-row>
        </b-container>
    </section>
</template>

<style scoped>
.group{
    border:0px;
    font-family: Open Sans;
}
.wOutShadow{
    box-shadow:20px 20px 50px grey;
    margin-bottom: 8rem;
}
.theItemSpace{
    
    width: 66%;
    display: inline-block;
    color: grey;

    
}

.theItemSpaceL{
    width: 33%;
    display: inline-block;
    font-weight: 700;
}
.buttonMargin{
    margin-left:1rem;
    margin-top: 1rem;
    background:#464d89;
    font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; 

}

h2, h4, h3, p{
    font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; 

}
</style>
