<template>
  <div>

    <hello-there-card/>
    <about-me-card/>
    <skills-cards/>
    <exp-card/>
    <comp-skills/>
    <thanks/>

  </div>
</template>

<script>
import AboutMeCard from '@/components/Cards/AboutMeCard'
import HelloThereCard from '@/components/Cards/HelloThereCard'
import SkillsCards from '@/components/Cards/SkillsCards'
import ExpCard from '@/components/Cards/ExpCard'
import compSkills from '@/components/Cards/compSkills'
import Thanks from '@/components/Cards/Thanks'

export default {
  components: {
    AboutMeCard,
    HelloThereCard,
    SkillsCards,
    ExpCard,
    compSkills,
    Thanks
  }
}
</script>