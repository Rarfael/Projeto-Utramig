<template>
  <div>
    <app-header></app-header>
      <app-section-top></app-section-top>
    <section class="sobre-section bg-light">
      <app-section-sobre></app-section-sobre>
    </section>
    <app-section-iphone></app-section-iphone>
    <app-section-conheca></app-section-conheca>
    <app-section-hardware></app-section-hardware>
    <app-footer></app-footer>

  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import SectionTopo from './components/SectionTopo.vue'
import SectionSobre from './components/SectionSobre.vue'
import SectionIphone from './components/SectionIphone.vue'
import SectionConheca from './components/SectionConheca.vue'
import SectionHardware from './components/SectionHardware.vue'

export default{
  components: {
    'app-header': Header,
    'app-footer': Footer,
    'app-section-top': SectionTopo,
    'app-section-sobre': SectionSobre,
    'app-section-iphone': SectionIphone,
    'app-section-conheca': SectionConheca,
    'app-section-hardware': SectionHardware
  }
}
</script>

<style>
body {
  background: #333;
  color: #FFF; }

  .sobre-section{
      padding: 100px;
    }
</style>
