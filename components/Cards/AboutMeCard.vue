<template>
    <section id="about-me">
        <b-container class="wOutShadow">
            <b-row>
                <b-col md="8">
                    <h2 style="margin-top:1rem;">About Me</h2>
                </b-col>
            </b-row>
            <b-row>
                <b-col lg="4" style="margin-bottom:2rem;">
                    <b-list-group>
                        <b-list-group-item class="group"><span class="theItemSpace">Name:</span>Jethzabell Medina</b-list-group-item>
                        <b-list-group-item class="group"><span class="theItemSpace">Phone:</span>+1 787 420 7746</b-list-group-item>
                        <b-list-group-item class="group"><span class="theItemSpace">Email:</span>jethzabell.medina@gmail.com</b-list-group-item>
                        <b-list-group-item class="group"><span class="theItemSpace">State:</span>Raleigh-Durham, NC</b-list-group-item>
                        <b-list-group-item class="group"><span class="theItemSpace">Bilingual:</span>Spanish and English</b-list-group-item>
                    </b-list-group>
                     <b-button class="buttonMargin" size="lg" href="https://drive.google.com/file/d/1RZCQXQ5BeiSLvhz4WvQFQes2W-1AWdhx/view?usp=sharing">Download my Resume</b-button>
                </b-col>
                <b-col lg="8">
                    <h4 style="margin-top:0.5rem;">Hi There</h4>
                    <p>I am Jethzabell, a young profesional with experience in Software Development, Software Enginieering and self-made front-end web developer - born in San Juan, PR.
                        <br>I'm currently aplying for a master degree in Computer Science, expected to graduate in 2021. 
                        <br>I've used technologies like <code>Vue.js(Nuxt), Node.js(Express.js), MongoDB</code> and plenty more!</p>

                        <p>My main programming language was <code>C++</code>, but now I work more with Web Development. 
                        <br><code>C++</code> was the language that I used(4yr) during my BS in <code>Computer Science</code>.</p>
                        <p>Currently I work in <code>IBM</code> as a Software Enginieer.</p>
                        <p>I spend most of my spare time coding, playing basketball, and traveling around the world.</p>
                    
                    <ul class="list-inline">
                        <li class="list-inline-item">
                            <a href="https://www.linkedin.com/in/jethzabell-medina/"><b-img src="/linkedIn.png"/></a>
                        </li>
                        <li class="list-inline-item">
                            <a href="https://github.com/Jethzabell"><b-img src="/github.png"/></a>
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
}
.wOutShadow{
    box-shadow:20px 20px 50px grey;
    margin-bottom: 3rem;
}
.theItemSpace{
    margin-right:3rem;
}
.buttonMargin{
    margin-left:1rem;
    margin-top: 1rem;
    background:#464d89;
}
</style>
