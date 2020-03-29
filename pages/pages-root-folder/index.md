---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Salabim Discrete Modeling Tutorial"
  url: '/modeling/salabim-discrete-modeling/'
  image: water-well-collection.webp
  text: 'Using a DES model to simulate women queueing at a water collection point.'
widget2:
  title: "System Dynamics Modeling for Neglected Tropical Diseases"
  url: '/modeling/NTD-system-dynamics/'
  text: 'Application of system dynamics modeling to an understudied public health problem.'
  image: widget-1-302x182.jpg
widget3:
  title: "Many-Objective Evolutionary Algorithms"
  url: '/tutorial/many-objective-evolutionary-algorithms/'
  image: rob3.webp
  text: 'An easy introduction to many-objective evolutionary algorithms and what they mean for policy analysis..'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
