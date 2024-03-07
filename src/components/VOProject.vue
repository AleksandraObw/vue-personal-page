<script>
export default {
    props: {
        item: {
            type: Object,
            required: true
        },
}
}
</script>

<template>
    <li>
        <h3>{{ item.title }}</h3>
        <img :src="item.image">
        <p>{{ item.description }}</p>
        <p><a :href="item.link" target="_blank">Link</a> | <a :href="item.github" target="_blank">GitHub</a> | <a :href="item.figma" target="_blank">Figma</a></p>
    </li>
</template>

<style scoped>
    li {
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: start;
        width: 200px;
    }
    img {
        width: 200px;
    }
    h3 {
        text-align: center;
        margin-top: 16px;
        margin-bottom: 8px;
    }
</style>