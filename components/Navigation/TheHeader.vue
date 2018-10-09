<template>

  <b-navbar toggleable="md" type="light" variant="faded" class="wOutShadow" >

    
    <b-navbar-brand href="#">
      <img src="/milogo.png" height="100px" class="d-inline-block align-top" alt="JM">
    </b-navbar-brand>
  
    <b-collapse is-nav id="nav_collapse" class="middle">
        <nuxt-link to="/">
        <h5>About Me</h5>
        </nuxt-link>

        <nuxt-link to="/projects">
        <h5>Projects</h5>
        </nuxt-link>
    </b-collapse>
  </b-navbar>

</template>

<style scoped>
.wOutShadow{
    box-shadow:20px 20px 50px grey;
}

.middle{
  margin-left:27%;
}

h5{
    color:#464d89;
    padding-right:1.5rem;
  }
</style>