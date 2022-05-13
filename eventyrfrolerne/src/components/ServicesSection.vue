<template>
    <section>
        <NavTo section="services"/>
        <Heading2 heading="Services"/>
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import Heading2 from "@/components/Heading2.vue"

export default {
    name: "ServicesSection",
    components: {
        NavTo,
        Heading2,
    }
}
</script>

<style lang="scss" scoped>

</style>