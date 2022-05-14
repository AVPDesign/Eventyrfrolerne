<template>
    <div>
        <h3>{{ frol.name }}</h3>
        <p>{{ frol.info }}</p>
    </div>
</template>

<script>
export default {
    name: "FrolComponent",
    props: {
        frol: Object,
    }
}
</script>

<style lang="scss" scoped>

</style>