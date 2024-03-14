<script>
  import FMProject from '../components/FMProject.vue'
  import jsonData from '../assets/frontendmentor.json'
  import ListVuejs from '../components/ListVuejs.vue'
  import ListJs from '../components/ListJs.vue'
  import ListVerstaemonline from '../components/ListVerstaemonline.vue'

  export default {
    data() {
        return {
            frontendmentor: jsonData
        };
    },
    props: 'typesection',
    components: {
      FMProject,
      ListVuejs,
      ListJs,
      ListVerstaemonline
    }
  }
</script>

<template>
    <h1>Projects</h1>
    <p>Since I don't have commercial development experience, this section contains training projects and exercises I've done.</p>
    <div class="page">

      <div class="projects_vuejs">
        <h3>Projects made with VueJS</h3>
        <div class="listing">
          <ListVuejs />
        </div>
      </div>

      <div class="projects_vanillajs">
        <h3>Projects made with VanillaJS</h3>
        <div class="listing">
          <ListJs />
        </div>
      </div>

      <div class="projects_verstaemonline">
        <h3>Projects made with Verstaem.Online layouts</h3>
        <div class="listing">
          <ListVerstaemonline />
        </div>
      </div>
 
      <div class="projects_frontendmentor">
        <h3>Frontendmentor challenges</h3>
        <div class="listing">
          <ul class="fm-list">
            <FMProject 
                      v-for="item of frontendmentor"
                      v-bind:item="item"
            />
          </ul>
        </div>
      </div>

      <!-- <div class="projects_wordpress">
        <h3>WordPress projects</h3>
        <div class="listing">
          <ProjectsList v-bind:typesection="wordpress" />
        </div>
      </div> -->

    </div>
</template>
  
  <style scoped>
    .page {
      display: flex;
      flex-direction: column;
      align-items: start;
      justify-content: center;
      row-gap: 8px;
      width: max(90%, 300px);
    }
    h3 {
      margin-top: 32px;
      margin-bottom: 8px;
    }
    .listing {
      display: flex;
      flex-direction: column;
      align-items: start;
      justify-content: center;
    }
    .listing::before {
      content: '';
      width: 300px;
      border: 1px solid #018185;
      display: flex;
      flex-direction: row;
      margin-bottom: 8px;
    }
    .fm-list {
      display: flex;
      flex-direction: column;
      row-gap: 1em;
    }
    .vo-list {
        display: flex;
        flex-direction: row;
        column-gap: 2em;
        row-gap: 1em;
        flex-wrap: wrap;
    }
  </style>