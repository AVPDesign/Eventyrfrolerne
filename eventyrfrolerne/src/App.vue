<template>
  <div class="global-wrapper">
    <MainHeader />
    <router-view />
    <MainFooter />
  </div>
</template>

<script>
// @ is an alias to /src
import MainHeader from "@/components/MainHeader.vue"
import MainFooter from "@/components/MainFooter.vue"

export default {
  name: "App",
  components: {
    MainHeader,
    MainFooter
  }
}
</script>

<style lang="scss">
// Variables
:root {
  --primary: #424242;
  --secondary: #8700e0;
  --tertiary: #fff;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

.global-wrapper {

}

.view-wrapper {

}
</style>
