<template>
    <section>
        <NavTo section="Services"/>
        <HeadingTwo heading="Services"/>
        <ServiceDisclaimer />
        <MenuList />
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import HeadingTwo from "@/components/HeadingTwo.vue"
import ServiceDisclaimer from "@/components/ServiceDisclaimer.vue"
import MenuList from "@/components/MenuList.vue"

export default {
    name: "ServicesSection",
    components: {
        NavTo,
        HeadingTwo,
        ServiceDisclaimer,
        MenuList,
    }
}
</script>

<style lang="scss" scoped>

</style>