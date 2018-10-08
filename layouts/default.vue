<template>
  <div>
    <TheHeader/>
    <nuxt/>
    <the-footer/>
  </div>
</template>

<script>
import TheHeader from '@/components/Navigation/TheHeader'
import TheFooter from '@/components/Navigation/TheFooter'

export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>


<style>
body {
  margin: 0;
  font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; 
  color: rgb(63, 63, 63);

}
</style>
