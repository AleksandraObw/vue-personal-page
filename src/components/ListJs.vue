<template>
    <ul>
        <li>
            <h3>Tic Tac Toe</h3>
            <div class="img1 img"></div>
            <p>HTML/CSS/JS. Tic Tac Toe game for 2 human players</p>
            <p><a href="https://tic-tac-toe-delta-ivory.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/tic-tac-toe" target="_blank">GitHub</a></p>
        </li>
        <li>
            <h3>To Do List</h3>
            <div class="img2 img"></div>
            <p>HTML/CSS/JS. To Do list</p>
            <p><a href="https://to-do-list-two-snowy.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/to-do-list" target="_blank">GitHub</a></p>
        </li>
        <li>
            <h3>Rock Paper Scissors</h3>
            <div class="img3 img"></div>
            <p>HTML/CSS/JS. Rock Paper Scissors game for 1 player</p>
            <p><a href="https://rock-paper-scissors-henna-ten.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/rock-paper-scissors" target="_blank">GitHub</a></p>
        </li>
        <li>
            <h3>Calculator</h3>
            <div class="img4 img"></div>
            <p>HTML/CSS/JS. Simple calculator</p>
            <p><a href="https://calculator-alpha-ashen.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/calculator" target="_blank">GitHub</a></p>
        </li>
        <li>
            <h3>Kanji Quiz</h3>
            <div class="img5 img"></div>
            <p>HTML/CSS/JS. Kanji quiz (N5 level)</p>
            <p><a href="https://n5-kanji-quiz.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/n5-kanji-quiz" target="_blank">GitHub</a></p>
        </li>
	<li>
            <h3>Momentum</h3>
            <div class="img6 img"></div>
            <p>HTML/CSS/JS. Momentum clone</p>
            <p><a href="https://momentum-two-puce.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/momentum" target="_blank">GitHub</a></p>
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
        background-size: contain;
        background-repeat: no-repeat;
    }
    .img1 {
        background-image: url("../assets/images/tictactoe.png");
    }
    .img2 {
        background-image: url("../assets/images/todolist.png");
    }
    .img3 {
        background-image: url("../assets/images/rockpaperscissors.png");
    }
    .img4 {
        background-image: url("../assets/images/calculator.png");
    }
    .img5 {
        background-image: url("../assets/images/kanjiquiz.png");
    }
    .img6 {
        background-image: url("../assets/images/momentum.png");
    }
    h3 {
        text-align: center;
        margin-top: 16px;
        margin-bottom: 8px;
    }
</style>