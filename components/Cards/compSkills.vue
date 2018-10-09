<template>
    <b-container style="padding-bottom:3rem;" >
        <h3>Development Skills</h3>
        <b-row class="wOutShadow">
            <b-col sm="8" >
                 <b-card-img src="/skills.png" />
            </b-col>
           
            <b-col sm="4"  >
                 <nuxt-link to="/projects">
                <h3>Projects & Training</h3>
                <b-card-img 
                    data-aos="zoom-in"
                    data-aos-delay="500" 
                    src="/training.svg" />
                 </nuxt-link>
            </b-col>
           
        </b-row>
    </b-container>
</template>

<style scoped>
.wOutShadow{
    box-shadow:20px 20px 50px grey;
    padding-top: 2rem;
    padding-bottom: 2rem;
}

h3{
  color: rgb(63, 63, 63);
}
</style>
