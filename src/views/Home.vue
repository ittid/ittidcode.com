<template lang="pug">
    section.main-content
      .lead
        .intro
          h1 Hi! 👋
          p I'm <strong>Abdessamad Ahnaine,</strong> a Front-End Web Developer Focused on Building Beautiful Interfaces 👨🏻‍💻
          .email 
            span get.inTouch() <sub class="hand">👉</sub>
            a(href="mailto:contact@ahnaine.com") ahnaine3bd@gmail.com

        .github-section
          a(href="https://github.com/ittid" target='_blank')
            .github 
              img(src="../assets/static/github.png", alt="alt")
      .clearfix    
      .Technology
        h1 Workwith<span>.skills( )</span>
        small // Frontend development, UX/UI design
        ul.skills
          li.html Html
          li.css Css
          li.sass Sass
          li.pug Pug
          li.js JS
          li.jq jQuery
          li.vue Vue
          li.gulp Gulp
      .projects
        h1 project<span>.selected( )</span>
        small //- Some special projects explained in details.
        ul.work-list
          li 
            a(href="https://nostalgic-joliot-fe1519.netlify.app" target="_blanck")
              .details
                h2 Gramutinc
                small //- Pugjs, Sass, JS
                span.comment Digital company focused on branding
          li 
            a(href="https://practical-joliot-8430aa.netlify.app/" target="_blanck")
              .details
                h2 Wydadistas
                small //- Html, Css, jQuery
                span.comment Website for Wydad Athletic Club fans &nbsp;                
</template>

<script>
// @ is an alias to /src*
export default {
  name: "Home",
};
</script>
