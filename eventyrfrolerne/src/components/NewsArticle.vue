<template>
    <div>
        <h3>{{ article.title }}</h3>
        <p>{{ article.date }}</p>
        <p>{{ article.text }}</p>
    </div>
</template>

<script>
export default {
    name: "NewsArticle",
    props: {
        article: Object,
    }
}
</script>

<style lang="scss" scoped>

</style>