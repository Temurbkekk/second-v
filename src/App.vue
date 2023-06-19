<template>
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;1,200;1,300;1,400&display=swap"
    rel="stylesheet">
  <div>
    <headerSection />
  </div>
  <div>
    <mainSection />
  </div>
  <featureSection />
  <efforlesValidation />
  <div>
    <EasierDecision />
  </div>
  <Optimisation />
  <NeedSuperHero />
  <MarketingStrategies />
  <footerSection />
</template>
<script>
import headerSection from '@/components/header-section/headerSection.vue'
import mainSection from '@/components/main-section/mainSection.vue'
import featureSection from '@/components/feature-section/featureSection.vue'
import efforlesValidation from '@/components/efforles-valudation/efforlesValidation.vue'
import EasierDecision from '@/components/Easier-decision-making/EasierDecision.vue'
import NeedSuperHero from '@/components/Need-super-hero/NeedSuperHero.vue'
import Optimisation from '@/components/Optimisation/Optimisation.vue'
import MarketingStrategies from '@/components/Marketing-strategies/MarketingStrategies.vue'
import footerSection from '@/components/footer-section/footerSection.vue'
export default {
  components: {
    headerSection,
    mainSection,
    featureSection,
    efforlesValidation,
    EasierDecision,
    NeedSuperHero,
    Optimisation,
    MarketingStrategies,
    footerSection,
  },
}
</script>
<style></style>
