<template>
    <ul>
        <li>
            <h3>Math Quiz</h3>
            <div class="img1 img"></div>
            <p>Math quiz for children (subtraction and addition of numbers up to 20)</p>
            <p><a href="https://vue-math-quiz.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/vue-math-quiz" target="_blank">GitHub</a></p>
        </li>
        <li>
            <h3>To Do List</h3>
            <div class="img2 img"></div>
            <p>To-do list. Add tasks and delete completed ones</p>
            <p><a href="https://vue-todolist-rho.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/vue-todolist" target="_blank">GitHub</a></p>
        </li>
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
    li {
        display: flex;
        flex-direction: column;
        align-items: start;
        justify-content: start;
        width: 200px;
    }
    .img {
        width: 200px;
        height: 220px;
        object-fit:scale-down;
    }
    .img2 {
        background-image: url("public/images/todolist.png");
    }
    .img1 {
        background-image: url("public/images/vue-mathquiz.png");
    }
    h3 {
        text-align: center;
        margin-top: 16px;
        margin-bottom: 8px;
    }
</style>