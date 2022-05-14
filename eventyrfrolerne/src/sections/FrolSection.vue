<template>
    <section>
        <NavTo section="Frol"/>
        <HeadingTwo heading="Frol"/>
        <FrolComponent 
            v-for="frol in frols" 
            :key="frol.id" 
            :frol="frol" 
        />
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import HeadingTwo from "@/components/HeadingTwo.vue"
import FrolComponent from "@/components/FrolComponent.vue"

export default {
    name: "FrolSection",
    components: {
        NavTo,
        HeadingTwo,
        FrolComponent,
    },
    data() {
        return {
            frols: [],
        };
    },
    created() {
        this.frols = [
            {
                id: 1,
                name: "Rødbede",
                info: "Lorem ipsum dolor sit amet...",
            },
            {
                id: 2,
                name: "Gulerod",
                info: "Lorem ipsum dolor sit amet...",
            },
            {
                id: 3,
                name: "Ranunkel",
                info: "Lorem ipsum dolor sit amet...",
            },
            {
                id: 4,
                name: "Kartoffel",
                info: "Lorem ipsum dolor sit amet...",
            },
            {
                id: 1,
                name: "Radisse",
                info: "Lorem ipsum dolor sit amet...",
            },
        ]
    }
}
</script>

<style lang="scss" scoped>

</style>