<script >
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Exp from '@/components/Experience.vue'
import Skills from '@/components/Skills.vue'
import About from '@/components/About.vue'
export default{
  components:{
    Header,
    Hero,
    Exp,
    Skills,
    About
  },

}
</script>

<template>
  <main class="container">

    <Header/>

    <Hero/>

    <Exp/>

    <Skills/>

    <About/>
  </main>

</template>

<style lang="scss" scoped>
.container{
  max-width: max(80%, 1200px);
  margin: 0 auto;
  
}
</style>
