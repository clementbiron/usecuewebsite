---
title: No Javascript
---


You probably load 100k jQuery in your page, because it makes programming soooo easy. But what if you want your page to be as small as 100k? Or usable by people who disable Javascript for security reasons (like many big companies in Germany)? Or just because you think that layout and fancy effects should be handled by CSS and not by javascript?

What does the 100k jQuery in your website actually do? I bet it toggles your hamburger menu, it might toggle some tabs… and, of course, it powers that enormous homepage slider. Here are your replacements/solutions:

* Off-screen navigation
  <br>No problem. Hiding and showing stuff was no problem with CSS, so all you need is the radio button hack, et voila… there you go: http://www.sitepoint.com/pure-css-off-screen-navigation-menu/
* Tabs
  <br>Useful for hiding and showing content. Same recipe: http://stanhub.com/create-responsive-tabs-using-css-only-no-jquery/
* Sliders
  <br>A little more complicated but also possible… Even with autoplay! Here are some examples: http://codepen.io/hw/pen/biEBz and http://xdesigns.net/2013/08/css-slider/


If you really MUST support IE8 or you want a more polished experience, you can use some conditional JS. But promise me to use it only when necessary, only to enhance the experience and that you use vanilla JS only. You do not want your site to be broken without JS. Seriously. Happy coding!