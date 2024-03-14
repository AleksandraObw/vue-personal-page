<template>
  <div class="about_page">
    <h1>About</h1>
      <div class="about_info">

        <h3>Hi there! 👋</h3>
        <div class="infoblock">
          <p><strong>Name:</strong> Aleksandra</p>
          <p><strong>Location:</strong> Krasnodar, RU</p>
          <p><strong>Education:</strong> Kuban State Technological University</p>
          <p>I don't have commercial development experience yet. I've worked as laboratory technician, chemical engineer and pc operator before. Currently i'm individual entrepreneur.</p>
          <p><strong>My passions</strong> 🤍 to code, to create, to learn foreign languages, to paint, to play games (pc or board games)</p>
          <a href="https://www.codewars.com/users/ayavl/badges/small" target="_blank">
            <img class="badge_img" src="https://www.codewars.com/users/ayavl/badges/small?theme=light" alt="codewars badge">
          </a>
        </div>

        <h3>Tools:</h3>
        <div class="infoblock">
          <ul class="tools_list">
            <li>            
              <img class="tool_img" src="https://img.icons8.com/fluency/32/html-5.png" alt="html5"/>
            </li>
            <li>
              <img class="tool_img" src="https://img.icons8.com/color/32/css3.png" alt="css3"/>
            </li>
            <li>
              <img class="tool_img" src="https://img.icons8.com/fluency/32/javascript.png" alt="javascript"/>
            </li>
            <li>
              <img class="tool_img" src="https://img.icons8.com/color/32/git.png" alt="git"/>
            </li>
            <li>
              <img class="tool_img" src="https://img.icons8.com/fluency/32/figma.png" alt="figma"/>
            </li>
            <li>
              <img class="tool_img" src="https://img.icons8.com/color/48/vue-js.png" alt="vue js"/>
            </li>
          </ul>   
          <div class="currently">
            <p class="">Currently learning:</p> 
            <ul class="tools_list">
              <li>
                <img class="tool_img" src="https://img.icons8.com/color/48/vue-js.png" alt="vue js"/>
              </li>
              <li>
                <img class="tool_img" src="https://img.icons8.com/color/48/sass.png" alt="sass"/>
              </li>
              <li>
                <img class="tool_img" src="https://img.icons8.com/color-glass/32/bootstrap.png" alt="bootstrap"/>
              </li>
              <li>
                <img class="tool_img" src="https://img.icons8.com/color/48/tailwind_css.png" alt="tailwind css"/>
              </li>
              <li>
                <img class="tool_img" src="https://img.icons8.com/color/48/wordpress.png" alt="wordpress"/>
              </li>
            </ul>       
          </div>
        </div>

        <h3>Languages:</h3>    
        <div class="infoblock"> 
          <ul>
            <li>Russian - native</li>
            <li>English - intermediate</li>
          </ul>
        </div>

        <h3>Socials & other links:</h3>
        <div class="infoblock">
          <ul class="tools_list">
            <li>
              <a href="https://t.me/AlexandraObw" target="blank"><img class="tool_img" src="https://img.icons8.com/color/32/telegram-app--v1.png"></a>
            </li>
            <li>
              <a href="https://github.com/AleksandraObw" target="blank" rel="norefferer noopener"><img class="tool_img" src="https://img.icons8.com/glyph-neue/64/github.png"></a>
            </li>
            <li>
              <a href="https://www.codewars.com/users/ayavl" target="blank" rel="norefferer noopener"><img class="tool_img" src="https://img.icons8.com/plasticine/100/codewars.png"></a>
            </li>
          </ul>          
        </div>
           
      </div>
    </div>
</template>

<style scoped>
  .about_page {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .about_info {
    display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: center;
    row-gap: 8px;
    width: max(50%, 300px);
  }
  h3:not(:first-of-type) {
    margin-top: 16px;
    margin-bottom: 8px;
  }
  .currently {
    display: flex;
    flex-direction: row;
    column-gap: 1em;
  }
.infoblock {
  display: flex;
  flex-direction: column;
  align-items: start;
  justify-content: center;
}
  .infoblock::before {
    content: '';
    width: 300px;
    border: 1px solid #018185;
    display: flex;
    flex-direction: row;
    margin-bottom: 8px;
  }
  .tool_img {
    width: 2em;
    height: 2em;
  }

  li {
    list-style-type: none;
  }
  .tools_list {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    column-gap: .5em;
  }
  .badge_img {
    margin: 8px;
  }
</style>