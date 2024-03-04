<script>
import Project from '@/components/Project.vue'

export default {
    props: {
        typesection: {
            type: Object,
            required: true
        },
    },
    components: { 
        Project 
    }    
}
</script>

<template>
    <ul>
        <Project
            v-for="item of typesection"
            v-bind:item="item"
            />
    </ul>
</template>

<style scoped>
    ul {
        display: flex;
        flex-direction: row;
        column-gap: 2em;
        row-gap: 1em;
        flex-wrap: wrap;
    }
</style>