<template>
  <div class="page">
    <div class="col col1">
      <div class="inner">
        <h1>Matt Bedford</h1>
        <h3>Full Stack Developer with PHP and JavaScript</h3>
        <p>Full-stack dev with PHP and JavaScript frameworks.
          I love to build projects and apps with companies who
          are trying to make the world a better place.</p>
      </div>
      <socialsVue />
    </div>

    <div class="col col2"></div>
  </div>
</template>

<script>
import socialsVue from './components/socials-vue.vue'

export default {
  name: 'App',
  components: {
    socialsVue
  }
}
</script>

<style>
/*Reset*/
* {
  text-align:left;
}
body {
 margin: 0;
 background:#363636;
}
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
  display: block;
}
body {
  line-height: 1;
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}

/*Custom*/
h1, h2, h3 {
  margin-bottom:15px;
}
h1 {
  font-weight:800;
  text-transform:uppercase;
  font-size:40px;
  line-height:50px;
}
h2 {
  font-size:30px;
  line-height:36px;
  font-weight:600;
}
h3 {
  font-size:20px;
  line-height:24px;
  font-weight:600;
}
p {
  font-size:16px;
  line-height:22px;
  font-weight:300;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  width:100%;
  margin:0;
  min-height:100vh;
  height:100%;
  position:fixed;
}
.page {
  display:flex;
  width:100%;
  max-width:1000px;
  margin:50px auto;
  height:100%;
  min-height:100vh;
}
.col {
  flex:0 1 50%;
  padding:40px;
}
.col1 {

}
.col2 {
  overflow-y:auto;
  background:red;
}

</style>
