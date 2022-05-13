<template>
    <section>
        <NavTo section="welcome"/>
        <Heading2 heading="Welcome"/>
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import Heading2 from "@/components/Heading2.vue"

export default {
    name: "WelcomeSection",
    components: {
        NavTo,
        Heading2,
    }
}
</script>

<style lang="scss" scoped>

</style>