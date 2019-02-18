---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "whitebackground.png"
widget1:
  title: "Getting Connected"
  url: 'https://tenet-rccpii.github.io/rccpii-2018/connectivity'
  image: connect.jpg
  text: 'Since 2010 <em>RCCP I</em> and <em>RCCP II</em> have been working with stakeholders to bring Internet connectivity to various higher education and research sites around South Africa. The project is a collaboration between DHET, USAF, TENET, and others.'
widget2:
  title: "Communicate & Collaborate"
  url: 'https://tenet-rccpii.github.io/rccpii-2018/econversations'
  text: 'Between January 2018 and March 2019 <em>RCCP II</em> will provide many opportunities for academic and support staff to get together and learn from each other and from various local and international experts. A large focus will be on online communication and collaboration. See you online!'
  image: collaborate.jpg
widget3:
  title: "Developing Human Capacity"
  url: 'https://tenet-rccpii.github.io/rccpii-2018/images/RCCPII_ToC2018-03-12.pdf'
  text: 'Learn more about the <em>RCCP II</em> Capacity Development Initiative. We have developed a Theory of Change document to show exactly who the intended audiences are, what we aim to provide, how we will work and what the intended outcomes will be. We look forward to be working with our communities.'
  image: home-never-stop-learning.png
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
  url: https://calendar.google.com/calendar/embed?src=beg31jqblfp9bb2sd8eba2fpgs%40group.calendar.google.com&ctz=Africa%2FJohannesburg
  text: View and subscribe to the RCCP II events calendar ›
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
