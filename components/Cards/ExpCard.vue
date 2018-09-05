<template>
    <b-container style="padding-bottom:3rem;">
        <h3>Experience</h3>
    <b-row>
    <b-card-group deck class="wInShadow">
        <b-card
                img-src="/ibmLogo.jpg"
                img-alt="Img"
                img-top
                class="wOutShadow"
                style="text-align:center;">
                <h5>Software Enginieer <br> Datapower Gateway & API Connect</h5>
        </b-card>
        <b-card 
                img-src="/USACE.jpg"
                img-alt="Img"
                img-top
                class="wOutShadow"
                style="text-align:center;">
                <h5>Software Developer <br> (Secret Clearance)</h5>
        </b-card>
        <b-card 
                img-src="/medirec.jpg"
                img-alt="Img"
                img-top
                class="wOutShadow"
                style="text-align:center;">
                <h4>Software Developer</h4>
        </b-card>
    </b-card-group>
    </b-row>
</b-container>
</template>


<script>
export default {
  data () {
    return {
      modalShow: false
    }
  }
}
</script>

<style scoped>
.wOutShadow{
    box-shadow:20px 20px 50px grey;
}
</style>
