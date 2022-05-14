<template>
    <div>
        <h3>{{ announcement.heading }}</h3>
        <p>{{ announcement.text }}</p>
    </div>
</template>

<script>
export default {
    name: "AnnouncementBanner",
    props: {
        announcement: Object,
    }
}
</script>

<style lang="scss" scoped>

</style>