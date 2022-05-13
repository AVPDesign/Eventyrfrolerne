<template>
    <section>
        <NavTo section="schedule"/>
        <Heading2 heading="Schedule"/>
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import Heading2 from "@/components/Heading2.vue"

export default {
    name: "ScheduleSection",
    components: {
        NavTo,
        Heading2,
    }
}
</script>

<style lang="scss" scoped>

</style>