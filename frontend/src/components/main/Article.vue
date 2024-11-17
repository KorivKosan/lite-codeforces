<template>
    <article>
        <div class="title">
            {{ post.title }}
        </div>
        <div class="information">By {{post.user.login}}, {{post.creationTime}}</div>
        <div class="body">
            {{ post.text }}
        </div>
    </article>
</template>


<script>
export default {
    name: "Article",
    props: ["post"]
}
</script>