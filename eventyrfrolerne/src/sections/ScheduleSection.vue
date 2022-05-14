<template>
    <section>
        <NavTo section="Schedule"/>
        <HeadingTwo heading="Schedule"/>
        <BusinessHours />
        <ScheduleTable />
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import HeadingTwo from "@/components/HeadingTwo.vue"
import BusinessHours from "@/components/BusinessHours.vue"
import ScheduleTable from "@/components/ScheduleTable.vue"

export default {
    name: "ScheduleSection",
    components: {
        NavTo,
        HeadingTwo,
        BusinessHours,
        ScheduleTable,
    }
}
</script>

<style lang="scss" scoped>

</style>