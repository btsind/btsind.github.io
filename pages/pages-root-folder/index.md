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
  title: "Jimin's Dance Mastery"
  url: 'https://www.instagram.com/reel/CoPBLFPp8pY/'
  image: jimin_medley.jpg
  text: "Jimin stuns fans with seamless dance moves in latest BTS medley featuring I Need U, Run, Dope, and Fire. The Main Dancer's incredible skills leave viewers in awe."
widget2:
  title: "J-Hope Unleashes Fire and Brimstone in All New Hope for BTS' Me, Myself, & Project"
  url: 'https://www.instagram.com/p/CoPkqGXrWcl/'
  text: "BTS' multi-talented rapper and dancer J-Hope is back with a new release, All New Hope, as part of the boy band's special 8-photo-folio pictorial project Me, Myself, &. J-Hope's teaser images showcase his transformation from an angelic look to a fiery and intense persona, giving fans a glimpse of what to expect from his latest release."
  image: jhope_album.jpg
# widget3:
#   title: "Download Theme"
#   url: 'https://github.com/Phlow/feeling-responsive'
#   image: widget-github-303x182.jpg
#   text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
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
