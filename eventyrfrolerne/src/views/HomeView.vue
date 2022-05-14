<template>
  <div class="view-wrapper">
    <WelcomeSection />
    <ScheduleSection />
    <NewsSection />
  </div>
</template>

<script>
// @ is an alias to /src
import WelcomeSection from "@/sections/WelcomeSection.vue"
import ScheduleSection from "@/sections/ScheduleSection.vue"
import NewsSection from "@/sections/NewsSection.vue"

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