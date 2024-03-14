<template>
    <ul>
        <li>
            <h3>Pioneer</h3>
            <div class="img1 img"></div>
            <p>Verstaem.online - Pioneer. HTML/CSS</p>
            <p><a href="https://from-figma-pioneer.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/fromFigma_pioneer" target="_blank">GitHub</a> | <a href="https://www.figma.com/file/rTIAAgDAufAPl61AWjYlrb/Пионер?type=design&node-id=0%3A1&t=b3RT1bbZuVZzaOfN-1" target="_blank">Figma</a> </p>
        </li>
        <li>
            <h3>InkHouse</h3>
            <div class="img2 img"></div>
            <p>Verstaem.online - inkHouse. HTML/CSS/JS</p>
            <p><a href="https://from-figma-ink-house.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/fromFigma_inkHouse" target="_blank">GitHub</a> | <a href="https://www.figma.com/file/SjHvI8W1yzwJjzyUrCPpsI/House?type=design&node-id=3%3A838&t=VZiVKXvlLixjtJN8-1" target="_blank">Figma</a></p>
        </li>
        <li>
            <h3>F&B</h3>
            <div class="img3 img"></div>
            <p>Verstaem.online - FB. HTML/SASS/JS</p>
            <p><a href="https://from-figma-fb.vercel.app/" target="_blank">Link</a> | <a href="https://github.com/AleksandraObw/fromFigma_FB" target="_blank">GitHub</a> | <a href="https://www.figma.com/file/fG61Ja1ye0jtkKbuvt9OR0/%D0%9A%D0%BE%D0%BB%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D1%8F-%D0%BF%D1%80%D0%B8%D1%80%D0%BE%D0%B4%D0%BD%D1%8B%D1%85-%D0%B0%D1%80%D1%82%D0%B5%D1%84%D0%B0%D0%BA%D1%82%D0%BE%D0%B2?type=design&node-id=0%3A1&mode=design&t=eiPphBBbc5LSCPAZ-1" target="_blank">Figma</a> </p>
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
        background-image: url("../assets/images/pioneer.png");
    }
    .img2 {
        background-image: url("../assets/images/inkhouse.png");
    }
    .img3 {
        background-image: url("../assets/images/fb.png");
    }
    h3 {
        text-align: center;
        margin-top: 16px;
        margin-bottom: 8px;
    }
</style>