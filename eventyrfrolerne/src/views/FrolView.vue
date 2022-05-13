<template>
  <div class="view-wrapper">
    <ServicesSection />
    <FrolSection />
  </div>
</template>

<script>
// @ is an alias to /src
import ServicesSection from "@/components/ServicesSection.vue"
import FrolSection from "@/components/FrolSection.vue"

export default {
  name: "HomeView",
  components: {
    ServicesSection,
    FrolSection,
  }
}
</script>

<style lang="scss" scoped>

</style>
