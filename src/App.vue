<template>
  <div>
    <MyHeader/>
    <Hero/>
    <HeroNav/>
    <Intro/>
    <VideoSection/>
    <Section/>
    <ReadMore/>
    <SeeMore/>
    <Footer/>
  </div>
</template>

<script>
  import MyHeader from './components/Header.vue'
  import Hero from './components/Hero.vue'
  import Intro from './components/Intro.vue'
  import VideoSection from './components/VideoSection.vue'
  import Section from './components/Section.vue'
  import ReadMore from './components/ReadMore.vue'
  import SeeMore from './components/SeeMore.vue'
  import Footer from './components/Footer.vue'
  import HeroNav from './components/HeroNav.vue'

  export default {
    name: 'App',
    components: {
      MyHeader,
      Hero,
      Intro,
      VideoSection,
      Section,
      ReadMore,
      SeeMore,
      Footer,
      HeroNav,
    }
  }
</script>

<style>
@import url(https://fonts.googleapis.com/css?family=Roboto|Work+Sans:500,600&amp;display=swap);
@import url(https://fonts.googleapis.com/css2?family=Roboto&display=swap);

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/
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

html {
  box-sizing: border-box;
}

*, *::after, *::before {
  box-sizing: inherit;
}

body {
  font-family: 'Work Sans',sans-serif;
  font-size: 16px;
  line-height: 1.3;
}

.container {
  width: 100%;
  max-width: 1110px;
  margin: 0 auto;
}
path {
  fill: currentColor;
}
.header {
  display: flex;
  justify-content: space-between;
}
</style>
