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
                <br>I'm <code>self organize</code>, <code>collaborative</code> and
                <br>enjoy working in an <code>Agile</code> enviroment.
                <br><code>Life Fact</code>: Basketball Player {College}.
                <br>But I also have the keys to be 
                <br><code>Independent</code>: Self-awareness, Self-motivation, and Self-regulation.

            </p> 
    
            
        </b-card>
        <b-card title="Self-made"
               img-src="/selfmade.png"
                img-alt="Img"
                img-top
                class="wOutShadow">
            <p class="card-text">
                I always look for inspiring resources, and I spend a lot of time learning by myself. 
                <code>Vue(Nuxt)</code>, 
                <code>React(Redux)</code>,
                <code>Node(Express)</code> and
                <code>MongoDB</code> are part of the new things I am learning.
            </p>
        </b-card>
        <b-card title="Software Engineering"
                img-src="/softeng.png"
                img-alt="Img"
                img-top
                class="wOutShadow">
            <p class="card-text">
                I have been into with web applications now and I worked with tech like:
                <code>C++, Java, Vue.js, Node.js</code>.
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
