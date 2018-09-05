<template>
    <b-container style="padding-bottom:3rem;">
        <h3>Focus and Skills</h3>
    <b-row>
    <b-card-group deck>
        <b-card title="Team Spirit"
                img-src="/team.png"
                img-alt="Img"
                img-top
                class="wOutShadow">
            <p class="card-text">
                Really keen on Team Work.
                <br>I'm <code>self organize</code>, <code>collaborative</code> and
                <br>enjoy working in an <code>Agile</code> enviroment.
                <br>Life Fact: Basketball Player {College}
            </p> 
    
            
        </b-card>
        <b-card title="Self-made"
               img-src="/selfmade.png"
                img-alt="Img"
                img-top
                class="wOutShadow">
            <p class="card-text">
                I always look for inspiring resources, and I spend a lot of time learning by myself. 
                <code>Vue(Nuxt), Node(Express), MongoDB, Mocha.js</code>  are part of the new things I am learning.
            </p>
        </b-card>
        <b-card title="Software Engineering"
                img-src="/softeng.png"
                img-alt="Img"
                img-top
                class="wOutShadow">
            <p class="card-text">
                I have been tinkering with web applications now and I worked with tech like:
                <code> Vue.js, Node.js, C++</code>.
            </p>
        </b-card>
    </b-card-group>
    </b-row>
</b-container>
</template>


<style scoped>
.wOutShadow{
    box-shadow:20px 20px 50px grey;
}
</style>