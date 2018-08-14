---
ID: 1524
post_title: test
author: lisa
post_excerpt: ""
layout: page
permalink: https://lisamittoo.ca/wp/test/
published: true
post_date: 2018-08-14 20:47:05
---
<script src='//static.codepen.io/assets/editor/live/console_runner-ce3034e6bde3912cc25f83cccb7caa2b0f976196f2f2d52303a462c826d54a73.js'></script><script src='//static.codepen.io/assets/editor/live/css_live_reload_init-e9c0cc5bb634d3d14b840de051920ac153d7d3d36fb050abad285779d7e5e8bd.js'></script>

<style class="cp-pen-styles">@import url("https://fonts.googleapis.com/css?family=Corben:700");<br />
h1 {<br />
  font-family: 'Corben', cursive;<br />
  font-size: 6rem;<br />
  color: white;<br />
  letter-spacing: 0.1rem;<br />
  text-shadow: 0px 3px 3px rgba(0, 0, 0, 0.66);<br />
}</p>
<p>.hero {<br />
  background-image: radial-gradient(50% 176%, #253854 80%, #061922 100%);<br />
  min-height: 30rem;<br />
  position: relative;<br />
  overflow: hidden;<br />
  display: flex;<br />
  justify-content: center;<br />
  align-content: center;<br />
}<br />
.hero__content {<br />
  position: relative;<br />
  align-self: center;<br />
  padding: 3rem 0;<br />
}</p>
<p>.snow {<br />
  position: absolute;<br />
  min-width: 100vw;<br />
  min-height: 100vh;<br />
  height: 100%;<br />
  width: 100%;<br />
  top: 0;<br />
  left: 0;<br />
}</p>
<p>.snow .svg {<br />
  position: absolute;<br />
  width: 100%;<br />
  height: 100%;<br />
}</p>
<p>#snow-top-layer {<br />
  will-change: transform;<br />
  -webkit-transform: translateY(-768px);<br />
          transform: translateY(-768px);<br />
  -webkit-animation: fall 22.5s infinite linear;<br />
          animation: fall 22.5s infinite linear;<br />
}</p>
<p>#snow-bottom-layer {<br />
  will-change: transform;<br />
  -webkit-transform: translateY(-768px);<br />
          transform: translateY(-768px);<br />
  -webkit-animation: fall 45s infinite linear;<br />
          animation: fall 45s infinite linear;<br />
}</p>
<p>@-webkit-keyframes fall {<br />
  100% {<br />
    -webkit-transform: translateY(0);<br />
            transform: translateY(0);<br />
  }<br />
}</p>
<p>@keyframes fall {<br />
  100% {<br />
    -webkit-transform: translateY(0);<br />
            transform: translateY(0);<br />
  }<br />
}<br />
</style>

&nbsp;
<div class="hero">
<div class="snow">




































































</div>
<div class="hero__content">
<h1>SVG Snow</h1>
</div>
</div>
&nbsp;