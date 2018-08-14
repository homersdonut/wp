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
<!DOCTYPE html><html lang='en' class=''>
<head><script src='//static.codepen.io/assets/editor/live/console_runner-ce3034e6bde3912cc25f83cccb7caa2b0f976196f2f2d52303a462c826d54a73.js'></script><script src='//static.codepen.io/assets/editor/live/css_live_reload_init-e9c0cc5bb634d3d14b840de051920ac153d7d3d36fb050abad285779d7e5e8bd.js'></script><meta charset='UTF-8'><meta name="robots" content="noindex"><link rel="shortcut icon" type="image/x-icon" href="//static.codepen.io/assets/favicon/favicon-8ea04875e70c4b0bb41da869e81236e54394d63638a1ef12fa558a4a835f1164.ico" /><link rel="mask-icon" type="" href="//static.codepen.io/assets/favicon/logo-pin-f2d2b6d2c61838f7e76325261b7195c27224080bc099486ddd6dccb469b8e8e6.svg" color="#111" /><link rel="canonical" href="https://codepen.io/matchboxhero/pen/pWLOQb?editors=1100" />

<link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css'>
<style class="cp-pen-styles">@import url("https://fonts.googleapis.com/css?family=Lobster+Two");
h1 {
  font-family: 'Lobster Two', cursive;
  font-size: 5rem;
  text-shadow: 0px 1px 0px white;
  color: #343434;
}

.container {
  position: relative;
  z-index: 0;
  background-color: #ededed;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  overflow: hidden;
}

.pulse {
  z-index: -1;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
          transform: translate(-50%, -50%);
  max-width: 30rem;
}
.pulse circle {
  fill: #ff5154;
  -webkit-transform: scale(0);
          transform: scale(0);
  opacity: 0;
  -webkit-transform-origin: 50% 50%;
          transform-origin: 50% 50%;
  -webkit-animation: pulse 2s cubic-bezier(0.5, 0.5, 0, 1);
          animation: pulse 2s cubic-bezier(0.5, 0.5, 0, 1);
}
.pulse circle:nth-child(2) {
  fill: #7fc6a4;
  -webkit-animation: pulse 2s 0.75s cubic-bezier(0.5, 0.5, 0, 1);
          animation: pulse 2s 0.75s cubic-bezier(0.5, 0.5, 0, 1);
}
.pulse circle:nth-child(3) {
  fill: #e5f77d;
  -webkit-animation: pulse 2s 1.5s cubic-bezier(0.5, 0.5, 0, 1);
          animation: pulse 2s 1.5s cubic-bezier(0.5, 0.5, 0, 1);
}

@-webkit-keyframes pulse {
  25% {
    opacity: 0.4;
  }
  100% {
    -webkit-transform: scale(1);
            transform: scale(1);
  }
}

@keyframes pulse {
  25% {
    opacity: 0.4;
  }
  100% {
    -webkit-transform: scale(1);
            transform: scale(1);
  }
}
</style></head><body>
<div class="container">
	
	<h1>Pulse Animation</h1>
	
	<svg class="pulse" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
        <circle id="Oval" cx="512" cy="512" r="512"></circle>
        <circle id="Oval" cx="512" cy="512" r="512"></circle>
		<circle id="Oval" cx="512" cy="512" r="512"></circle>
</svg>
	
</div>

</body></html>