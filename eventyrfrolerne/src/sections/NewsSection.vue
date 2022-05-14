<template>
    <section>
        <NavTo section="News"/>
        <HeadingTwo heading="News"/>
        <TextArea 
            txt="
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ex suscipit, 
                cupiditate deserunt debitis aut, maxime nam sit assumenda dicta dolor 
                cumque magnam veritatis beatae delectus neque iure ratione, impedit sed!
            " 
        />
        <NewsArticle 
            v-for="article in articles" 
            :key="article.id" 
            :article="article" 
        />
    </section>
</template>

<script>
import NavTo from "@/components/NavTo.vue"
import HeadingTwo from "@/components/HeadingTwo.vue"
import TextArea from "@/components/TextArea.vue"
import NewsArticle from "@/components/NewsArticle.vue"

export default {
    name: "NewsSection",
    components: {
        NavTo,
        HeadingTwo,
        TextArea,
        NewsArticle,
    },
    data() {
        return {
            articles: [],
        };
    },
    created() {
        this.articles = [
            {
                id: 1,
                title: "Ny frugt på rodmarkedet",
                date: "01-01-1001",
                text: "Lorem ipsum dolor sit amet...",
            },
        ]
    }
}
</script>

<style lang="scss" scoped>

</style>