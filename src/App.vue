<script>
  // importo componenti
  import AppTitle from './components/AppTitle.vue'
  import AppHero from './components/AppHero.vue'
  import SliderSection from './components/SliderSection.vue'
  import BigImg from './components/BigImg.vue'
  import FooterMain from './components/FooterMain.vue'

  export default {
    name: 'App',
    components: {
      AppTitle,
      AppHero,
      SliderSection,
      BigImg,
      FooterMain,
    },
  }
</script>

<!-- template -->
<template>
  <header>
    <AppTitle />
  </header>

  <div>
    <AppHero />
  </div>

  <main>
    <!-- img slide-->
    <SliderSection />
    <!-- big img -->
    <BigImg />
  </main>

  <footer>
    <!-- footer -->
    <FooterMain /> 
  </footer>

</template>

<!-- style nel caso -->
<style></style>