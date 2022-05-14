<template>
    <section>
        <NavTo section="Welcome"/>
        <HeadingTwo heading="Welcome"/>
        <TextArea 
            txt="
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ex suscipit, 
                cupiditate deserunt debitis aut, maxime nam sit assumenda dicta dolor 
                cumque magnam veritatis beatae delectus neque iure ratione, impedit sed!
            " 
        />
        <AnnouncementBanner 
            v-for="announcement in announcements" 
            :key="announcement.id" 
            :announcement="announcement" 
        />
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import HeadingTwo from "@/components/HeadingTwo.vue"
import TextArea from "@/components/TextArea.vue"
import AnnouncementBanner from "@/components/AnnouncementBanner.vue"

export default {
    name: "WelcomeSection",
    components: {
        NavTo,
        HeadingTwo,
        TextArea,
        AnnouncementBanner,
    },
    data() {
        return {
            announcements: [],
        };
    },
    created() {
        this.announcements = [
            {
                id: 1,
                heading: "Rodfrugt søges!",
                text: "Lorem ipsum dolor sit amet...",
            },
        ]
    }
}
</script>

<style lang="scss" scoped>

</style>