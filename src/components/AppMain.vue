<script>
import ThemesSection from './sections/ThemesSection.vue';
import MigrantsSection from './sections/MigrantsSection.vue';
import EnvironmentSection from './sections/EnvironmentSection.vue';
import BusinessSection from './sections/BusinessSection.vue';
import UcraineSection from './sections/UcraineSection.vue';
export default{
  components: {
    ThemesSection,
    MigrantsSection,
    EnvironmentSection,
    BusinessSection,
    UcraineSection
  },
  data(){
    return{
      
    }
  }
}

</script>

<template>
  <!-- mobile -->
  <div class="d-block d-md-none">
    <ThemesSection />
    <MigrantsSection />
    <EnvironmentSection />
    <BusinessSection />
    <UcraineSection />
  </div>
  <!-- desktop -->
  <div class="d-none d-md-block">
    <ThemesSection />
    <div class="my_row_1">
      <MigrantsSection />
    </div>
    <div class="my_row_2">
      <div class="my_col">
        <EnvironmentSection />
      </div>
      <div class="my_col_2">
        <BusinessSection />
        <UcraineSection />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
      
</style>
