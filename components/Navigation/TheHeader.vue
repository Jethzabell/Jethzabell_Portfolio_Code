<template>
  <b-navbar toggleable="md" type="light" variant="faded" class="wOutShadow">

    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    <b-navbar-brand href="#">
      <img src="/milogo.png" height="100px" class="d-inline-block align-top" alt="JM">
    </b-navbar-brand>
    
    <b-collapse is-nav id="nav_collapse">

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">Home</b-nav-item>
        <b-nav-item href="#">Blog</b-nav-item>
      </b-navbar-nav>

    </b-collapse>

  </b-navbar>
</template>

<style scoped>
.wOutShadow{
    box-shadow:20px 20px 50px grey;
}
</style>