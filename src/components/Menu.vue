<script setup>
    import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <nav>
    <ul>
        <RouterLink to="/">
            <li class="home-icon">
                <div class="icon">
                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="50" height="50" viewBox="0 0 50 50">
                    <path d="M 24.962891 1.0546875 A 1.0001 1.0001 0 0 0 24.384766 1.2636719 L 1.3847656 19.210938 A 1.0005659 1.0005659 0 0 0 2.6152344 20.789062 L 4 19.708984 L 4 46 A 1.0001 1.0001 0 0 0 5 47 L 18.832031 47 A 1.0001 1.0001 0 0 0 19.158203 47 L 30.832031 47 A 1.0001 1.0001 0 0 0 31.158203 47 L 45 47 A 1.0001 1.0001 0 0 0 46 46 L 46 19.708984 L 47.384766 20.789062 A 1.0005657 1.0005657 0 1 0 48.615234 19.210938 L 41 13.269531 L 41 6 L 35 6 L 35 8.5859375 L 25.615234 1.2636719 A 1.0001 1.0001 0 0 0 24.962891 1.0546875 z M 25 3.3222656 L 44 18.148438 L 44 45 L 32 45 L 32 26 L 18 26 L 18 45 L 6 45 L 6 18.148438 L 25 3.3222656 z M 37 8 L 39 8 L 39 11.708984 L 37 10.146484 L 37 8 z M 20 28 L 30 28 L 30 45 L 20 45 L 20 28 z"></path>
                    </svg>
                </div>
            </li>
        </RouterLink>
        <RouterLink to="/about">
            <li class="about-icon">
                <div class="icon"> 
                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="50" height="50" viewBox="0 0 50 50">
                    <path d="M 25 2 C 12.309295 2 2 12.309295 2 25 C 2 37.690705 12.309295 48 25 48 C 37.690705 48 48 37.690705 48 25 C 48 12.309295 37.690705 2 25 2 z M 25 4 C 36.609824 4 46 13.390176 46 25 C 46 36.609824 36.609824 46 25 46 C 13.390176 46 4 36.609824 4 25 C 4 13.390176 13.390176 4 25 4 z M 25 11 A 3 3 0 0 0 22 14 A 3 3 0 0 0 25 17 A 3 3 0 0 0 28 14 A 3 3 0 0 0 25 11 z M 21 21 L 21 23 L 22 23 L 23 23 L 23 36 L 22 36 L 21 36 L 21 38 L 22 38 L 23 38 L 27 38 L 28 38 L 29 38 L 29 36 L 28 36 L 27 36 L 27 21 L 26 21 L 22 21 L 21 21 z"></path>
                    </svg>
                </div>
            </li>
        </RouterLink>
        <RouterLink to="/projects">
            <li class="projects-icon">
                <div class="icon">
                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="50" height="50" viewBox="0 0 50 50">
                    <path d="M 20 3 C 18.355469 3 17 4.355469 17 6 L 17 9 L 3 9 C 1.355469 9 0 10.355469 0 12 L 0 26.8125 C -0.0078125 26.875 -0.0078125 26.9375 0 27 L 0 44 C 0 45.644531 1.355469 47 3 47 L 47 47 C 48.644531 47 50 45.644531 50 44 L 50 12 C 50 10.355469 48.644531 9 47 9 L 33 9 L 33 6 C 33 4.355469 31.644531 3 30 3 Z M 20 5 L 30 5 C 30.5625 5 31 5.4375 31 6 L 31 9 L 19 9 L 19 6 C 19 5.4375 19.4375 5 20 5 Z M 3 11 L 47 11 C 47.5625 11 48 11.4375 48 12 L 48 26.84375 C 48 26.875 48 26.90625 48 26.9375 L 48 27 C 48 27.5625 47.5625 28 47 28 L 3 28 C 2.4375 28 2 27.5625 2 27 C 2.007813 26.9375 2.007813 26.875 2 26.8125 L 2 12 C 2 11.4375 2.4375 11 3 11 Z M 25 22 C 23.894531 22 23 22.894531 23 24 C 23 25.105469 23.894531 26 25 26 C 26.105469 26 27 25.105469 27 24 C 27 22.894531 26.105469 22 25 22 Z M 2 29.8125 C 2.316406 29.925781 2.648438 30 3 30 L 47 30 C 47.351563 30 47.683594 29.925781 48 29.8125 L 48 44 C 48 44.5625 47.5625 45 47 45 L 3 45 C 2.4375 45 2 44.5625 2 44 Z"></path>
                    </svg>
                </div>
            </li>
        </RouterLink>  
        <RouterLink to="/contacts">
            <li class="contacts-icon">
                <div class="icon">
                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="50" height="50" viewBox="0 0 50 50">
                    <path d="M 17 10 C 12.042969 10 8 14.042969 8 19 L 8 35 C 8 35.550781 8.449219 36 9 36 L 28 36 L 28 46 L 30 46 L 30 36 L 32 36 L 32 46 L 34 46 L 34 36 L 47 36 C 47.550781 36 48 35.550781 48 35 L 48 19 C 48 14.042969 43.957031 10 39 10 Z M 17 12 C 20.878906 12 24 15.121094 24 19 L 24 34 L 10 34 L 10 19 C 10 15.121094 13.121094 12 17 12 Z M 22.625 12 L 39 12 C 42.878906 12 46 15.121094 46 19 L 46 34 L 26 34 L 26 19 C 26 16.171875 24.675781 13.652344 22.625 12 Z M 32 17 C 30.894531 17 30 17.894531 30 19 C 30 20.105469 30.894531 21 32 21 C 32.738281 21 33.371094 20.597656 33.71875 20 L 39 20 L 39 24 L 43 24 L 43 18 L 33.71875 18 C 33.371094 17.402344 32.738281 17 32 17 Z M 13.71875 20 C 13.167969 20.078125 12.78125 20.589844 12.859375 21.140625 C 12.9375 21.691406 13.449219 22.078125 14 22 L 20 22 C 20.359375 22.003906 20.695313 21.816406 20.878906 21.503906 C 21.058594 21.191406 21.058594 20.808594 20.878906 20.496094 C 20.695313 20.183594 20.359375 19.996094 20 20 L 14 20 C 13.96875 20 13.9375 20 13.90625 20 C 13.875 20 13.84375 20 13.8125 20 C 13.78125 20 13.75 20 13.71875 20 Z"></path>
                    </svg>
                </div>
            </li>
        </RouterLink>
    </ul>
  </nav>
</template>

<style scoped>
    nav {
        background: transparent;  
    }
    ul {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
    } 
    svg {
        fill: #ffffff;
    }
    .icon {
        text-align: center;
    }
    li {
        list-style-type: none;
        background-color: #018185;
        cursor: pointer;
        text-transform: uppercase;
	    transition: all .7s ease-in-out;
        height: 100px;
        width: 100px;
        line-height: 125px;
        position: relative;
    }
    li:hover {
	    transform: translateY(-100px);
    }
    li::after {
        content: "";
        position: absolute;
        background: #ffffff;
        color: #018185;
        top: -100px;
        left: 0;
        width: 100px; 
        height: 100px;
        opacity: 0;
        transform-origin: 0 100%;
        transition: all .5s ease-out;
        text-align: center;
        font-weight: 500;
        line-height: 100px;
    }
    li:hover::after {
        opacity: 1;
        transform: translateY(100px);
        top: 0;
    }
    .home-icon::after { 
        content: "Home";
    }
    .about-icon::after { 
        content: "About";
    }
    .projects-icon::after { 
        content: "Projects";
    }
    .contacts-icon::after { 
        content: "Contacts";
    }

    @media (max-width: 400px) {
        li {
        width: 75px;
        height: 75px;
        font-size: .8em;
    }
    li:hover {
	    transform: translateY(-75px);
    }
    li::after {
        width: 75px; 
        height: 75px;
        font-size: 1em;
        line-height: 75px;
    }
    li:hover::after {
        opacity: 1;
        transform: translateY(75px);
        top: 0;
    }
    }
</style>