<template>
    <b-container style="padding-bottom:3rem;">
        <h3>Experience</h3>
    <b-row>
    <b-card-group deck>
        <b-card class="wOutShadow"
                data-aos="zoom-out"
                data-aos-delay="400">
            <b-img center src="/ibmLogo.png"/>
            <h3>Software Enginieer</h3>
            
            <p class="card-text">
               IBM DataPower Gateway is a single multi-channel gateway that helps provide
                security, control,integration and optimized access to a full range of mobile, web, API, SOA, B2B and cloud workloads.
            </p> 
        </b-card>
        <b-card class="wOutShadow" 
                data-aos="zoom-out"
                data-aos-delay="200">
            <b-img center  src="/USACE.png"/>
            <h3>Software Developer</h3>
            
            <p class="card-text">
                Developing a Mobile Information Collection Application (MICA) coded in QT C++
                libraries that can be run in any platform.
                Security Clearance with Army DoD.
            </p> 
        </b-card>
        <b-card class="wOutShadow"
                data-aos="zoom-out">
            <b-img center src="/medirec.png"/>
            <h3>Software Developer</h3>
            
            <p class="card-text">
                Create a complete Database Mapping that
                allow co-workers understand and re-design a new Database from MS SQL Server to MariaDB.
            </p> 
        </b-card>
    </b-card-group>
    </b-row>
</b-container>
</template>


<style scoped>
.wOutShadow{
    box-shadow:20px 20px 50px grey;
    text-align:center;
}

h3, p, h1{
  color: rgb(63, 63, 63);
}

</style>
