<template>
  <header>
      <nav>
        <router-link to="/">Home</router-link> |
        <router-link to="/frol">Frol</router-link>
      </nav>
    </header>
</template>

<script>
export default {
  name: "MainHeader",
  props: {
    msg: String
  }
}
</script>

<style lang="scss" scoped>

</style>