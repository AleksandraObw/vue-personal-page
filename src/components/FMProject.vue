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
        <h4> {{ item.title }} <span> {{ item.description }} </span></h4>
        <a :href="item.github" target="_blank">GitHub</a>
    </li>
</template>

<style scoped>
    li {
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: start;
    }
    h3 {
        text-align: center;
        margin-top: 16px;
        margin-bottom: 8px;
    }
    span {
        font-size: .8em;
        font-weight: 500;
    }
</style>