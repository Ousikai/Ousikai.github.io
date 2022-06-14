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
  title: "About"
  url: 'https://ousikai.github.io/about'
  image: widget-vr-302x182.jpg
  text: 'Welcome to the Tempest.'
widget2:
  title: "Ongoing Stories"
  url: 'https://ousikai.github.io/blog/ongoing-stories'
  image: widget-apps-302x182.jpg
  text: 'A storm wakes on the horizon.'
widget3:
  title: "Completed Stories"
  url: 'https://ousikai.github.io/blog/edge-of-eclipse'
  image: widget-tutorials-302x182.jpg
  text: 'Tales that have come to pass.'

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
  text: Subscribe to get the latest stories delivered to your inbox! ›
  style: alert
permalink: /index.html
homepage: true
---
