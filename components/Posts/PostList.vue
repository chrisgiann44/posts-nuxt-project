<template>
    <section class="post-list">
        <PostPreview
            id="1"
            title="Hello there!"
            previewText="This is a post"
            thumbnail="https://tradeandinvest.wales/sites/default/files/styles/standard_75_desktop_retina/public/tech_sector_image_1428x952px_2.jpg?itok=FpJLzqWT"
        />
        <PostPreview
            id="2"
            title="Hello there! 2"
            previewText="This is a post 2"
            thumbnail="https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fspecials-images.forbesimg.com%2Fdam%2Fimageserve%2F1160986680%2F960x0.jpg%3Ffit%3Dscale"
        />
        <PostPreview
            id="3"
            title="Hello there! 3"
            previewText="This is a post 3"
            thumbnail="https://www.bsr.org/images/heroes/tech-against-trafficking-hero.jpg"
        />
        <PostPreview
            id="4"
            title="Hello there! 4"
            previewText="This is a post 4"
            thumbnail="https://www.fairobserver.com/wp-content/uploads/2019/08/Tech-news.jpg"
        />
    </section>
</template>

<script>
import PostPreview from "@/components/Posts/PostPreview";

export default {
    components: {
        PostPreview
    }
};
</script>

<style scoped>
.post-list {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}
</style>