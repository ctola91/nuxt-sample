<template>
    <section>
        <h1>post</h1>
        <div v-html="postContent"></div>
    </section>
</template>
<script>
export default {
    computed: {
        post: () => {
            return {id: 'first-post'}
        },
        postContent: function() {
            let post = this.post;
            return require(`../../content/posts/${post.id}.md`)
        }
    }
}
</script>
<style lang="scss" scoped>

</style>
