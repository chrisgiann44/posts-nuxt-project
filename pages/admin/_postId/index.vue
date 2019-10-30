<template>
    <div class="admin-post-page">
        <section class="update-form">
            <AdminPostForm :post="loadedPost" />
        </section>
    </div>
</template>

<script>
import AdminPostForm from "@/components/Admin/AdminPostForm";
export default {
    components: {
        AdminPostForm
    },
    data() {
        return {
            loadedPost: {
                author: "Christos",
                title: "Amazing",
                content: "i am amazing",
                thumbnail:
                    "https://www.greeka.com/village_beach/photos/232/town-top-1-1280.jpg"
            }
        };
    }
};
</script>

<style scoped>
.update-form {
    width: 90%;
    margin: 20px auto;
}
@media (min-width: 768px) {
    .update-form {
        width: 500px;
    }
}
</style>