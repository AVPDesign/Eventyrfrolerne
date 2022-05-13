<template>
    <section>
        <NavTo section="news"/>
        <Heading2 heading="News"/>
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import Heading2 from "@/components/Heading2.vue"

export default {
    name: "NewsSection",
    components: {
        NavTo,
        Heading2,
    }
}
</script>

<style lang="scss" scoped>

</style>