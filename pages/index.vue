<template>
  <div>
    <Spinner v-if="showHideSpinner" />
    <!--<Navbar />-->
    <StartSegment />
    <ArrowSegment />
    <Projects />
    <AboutMe />
    <Skills />
    <Contact />
  </div>
</template>

<script>
export default {
  beforeCreate() {
    this.showHideSpinner = true
  },
  mounted() {
    //Its really pretty okey...
    setTimeout(() => (this.showHideSpinner = false), 500)
  },
  data() {
    return {
      showHideSpinner: true,
    }
  },
}
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>
