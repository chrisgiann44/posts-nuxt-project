<template>
    <div class="home-page">
        <section class="intro">
            <h1>Get the latest tech news!</h1>
        </section>
        <section class="featured-posts">
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
    </div>
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
.intro {
    height: 300px;
    position: relative;
    padding: 30px;
    box-sizing: border-box;
    background-image: url("~assets/images/main-page-background.jpg");
    background-position: center;
    background-size: cover;
}

.intro h1 {
    position: absolute;
    top: 10%;
    left: 5%;
    width: 90%;
    font-size: 1.5rem;
    color: black;
    background-color: rgb(211, 211, 211);
    padding: 10px;
    border-radius: 10px;
    box-shadow: 3px 3px 3px black;
    box-sizing: border-box;
    border: 1px solid black;
}

@media (min-width: 768px) {
    .intro h1 {
        font-size: 2rem;
    }
}

.featured-posts {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}
</style>
