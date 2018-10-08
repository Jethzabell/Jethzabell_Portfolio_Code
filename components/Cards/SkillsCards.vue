<template>
    <b-container style="padding-bottom:3rem;">
        <h3>Focus and Skills</h3>
    <b-row>
    <b-card-group deck>
        <b-card class="wOutShadow"
                data-aos="zoom-out">
            <b-img center src="/team.png"/>
            <h3>Team Spirit</h3>
            <p class="card-text">
                I'm self organize, collaborative and enjoy working in an Agile enviroment.
                <br>Life Fact: Basketball Athlete.
                But I also have the keys to be Independent: Self-awareness, Self-motivation, and Self-regulation.
            </p> 
        </b-card>
        <b-card class="wOutShadow"
                data-aos="zoom-out"
                data-aos-delay="200">
            <b-img center src="/selfmade.png"/>
            <h3>Self-made</h3>
            <p class="card-text">
                I always look for inspiring resources,
                and I spend a lot of time learning by myself. 
                Vue(Nuxt), React(Redux), Node(Express) and
                MongoDB are part of the new things I am learning.
            </p>
        </b-card>
        <b-card class="wOutShadow"
                data-aos="zoom-out"
                data-aos-delay="400">
            <b-img center src="/softeng.png"/>
            <h3>Software Engineering</h3>
            <p class="card-text">
                I have been into with web applications now and I worked with tech like:
                C++, Java, Vue.js, Node.js.
            </p>
        </b-card>
    </b-card-group>
    </b-row>
</b-container>
</template>


<style scoped>
.wOutShadow{
    text-align:center;
    box-shadow:20px 20px 50px grey;
}

h1, p, h3{
  color: rgb(63, 63, 63);
}

</style>