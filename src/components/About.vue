<template>
    <div>
        <p>
            I began by installing Node.js on my laptop, which also gave me access to npm (the Node Package Manager).
            Using npm, I created a new Vue project with Vite and installed all the necessary dependencies. After that, I
            built my webpage by modifying files such as App.vue, main.js, and index.html inside the project.
            Once the webpage was working locally, I generated a production build using the npm run build command.
            This created a dist folder containing the optimized files for deployment. To publish my site, I created a
            GitHub repository, uploaded my project files, and configured Vite so it could be hosted correctly on GitHub
            Pages. After pushing my project to GitHub, I enabled GitHub Pages to serve the contents of the dist folder.
        </p>
        <p style="font-weight: bold;">Challenges:</p>
        <p>
            I encountered several challenges while completing this problem. At first, I struggled to understand how
            Vue.js works, especially how components, App.vue, and main.js interact. I had to watch tutorials to fully
            understand the structure. Another major challenge was deployment. I followed multiple guides, but I still ran
            into many issues with Vite configuration and GitHub Pages hosting. After troubleshooting and testing
            different fixes, I eventually managed to get the website working online.
        </p>
    </div>
</template>

<script>
    export default{
    }
</script>

<style>
    div{
        text-align: center;
    }

    p{
        width: 80vw;
        color: black;
        font-size: 1.5vw;
    }
</style>