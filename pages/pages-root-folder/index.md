---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: fellowship.jpg
widget1:
  title: "The first Kovilan Memorial talk"
  url: '/journal/2011-06-01/'
  image: kovilan-memorial-talk-2011.jpg
  text: 'The first Kovilan Memorial talk was held at 3.30 pm on Wednesday, 1-6-2011, at the Kerala Sahitya Akademy Audutorium, in Thrissur, Kerala.'
widget2:
  title: "Short film"
  url: '/life-history/'
  text: '<em>Kovilan ente achachan</em> is a short film on Kovilan.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="images/kovilan-ente-achachan.png" width="302" height="182" alt=""/></a>'
widget3:
  title: "The first informal gathering"
  url: '/journal/2010-08-10/'
  image: first_meeting.jpg
  text: 'The first informal gathering of the Study Group at KOLOZHY, Thamarayur, Guruvayur, Kerala, India. P. Shamsudheen, K. A. Mohandas, Venu Edakkazhiyur, K.V. Subramanian, K.R. Vinayan.'
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
  url: https://tinyletter.com/the-international-kovilan-study-group
  text: Inform me about new updates ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/FT9kLbppNTs" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
