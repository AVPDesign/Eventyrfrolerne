<template>
  <div class="view-wrapper">
    <WelcomeSection />
    <ScheduleSection />
    <NewsSection />
  </div>
</template>

<script>
// @ is an alias to /src
import WelcomeSection from "@/components/WelcomeSection.vue"
import ScheduleSection from "@/components/ScheduleSection.vue"
import NewsSection from "@/components/NewsSection.vue"

export default {
  name: "HomeView",
  components: {
    WelcomeSection,
    ScheduleSection,
    NewsSection,
  }
}
</script>

<style lang="scss" scoped>

</style>