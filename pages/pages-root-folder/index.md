---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "A Tempest of Stars"
header:
  image_fullwidth: header_atos.jpg
widget1:
  title: "Edge of Eclipse"
  url: 'https://ousikai.github.io/blog/edge-of-eclipse'
  image: widget-vr-302x182.jpg
  text: 'Stories from the Future.'
widget2:
  title: "Perfecting Your Protagonist"
  url: 'https://ousikai.github.io/blog/perfecting-your-protagonist'
  image: widget-apps-302x182.jpg
  text: 'Chronicling the Present.'
widget3:
  title: "Blog"
  url: 'https://ousikai.github.io/blog/twilight-theater'
  image: widget-tutorials-302x182.jpg
  text: 'Ruminating on the Past.'

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
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
  url: https://tinyletter.com/Ousikai
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
homepage: true
---
