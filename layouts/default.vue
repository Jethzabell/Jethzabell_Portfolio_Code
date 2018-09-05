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
html {
  font-family: 'Open Sans', sans-serif;
}

body {
  margin: 0;
}
</style>
