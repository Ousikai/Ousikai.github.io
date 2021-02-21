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
  title: "Tempest Crossing"
  url: 'https://atemosta.com/tempest-crossing'
  image: widget-vr-302x182.jpg
  text: 'Discover the selves dwelling just beneath the surface.'
widget2:
  title: "Projects"
  url: 'https://atemosta.com/projects'
  image: widget-apps-302x182.jpg
  text: 'Streamlined solutions to simplify our unsystematic lives.'
widget3:
  title: "Blog"
  url: 'https://atemosta.com/blog'
  image: widget-tutorials-302x182.jpg
  text: 'Tutorials and musings through middle earth and the virtual unknown.'

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
  url: https://tinyletter.com/Atemosta
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
homepage: true
---
