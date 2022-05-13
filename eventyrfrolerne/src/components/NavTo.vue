<template>
    <a href="#">This is supposed to be an empty a tag for scrolling to the {{ section }} section using the nav bar</a>
</template>

<script>
export default {
  name: "NavTo",
  props: {
      section: String,
  }
}
</script>

<style lang="scss" scoped>

</style>