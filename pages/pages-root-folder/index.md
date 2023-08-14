---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: https://images.unsplash.com/photo-1480264104733-84fb0b925be3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mjh8fGJvZHklMjBidWlsZGVyfGVufDB8fDB8fHww&auto=format&fit=crop&w=600&q=60
widget1:
  title: "Realistic arm workout routine"
  url: "/arm-workout"
  image: https://images.unsplash.com/photo-1605296867304-46d5465a13f1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8Ym9keSUyMGJ1aWxkZXJ8ZW58MHx8MHx8fDA%3D&auto=format&fit=crop&w=600&q=60
  text: "When it comes to fitness goals, one area that many people aim to sculpt and strengthen is their arms. Having well-defined arms not only enhances your physical appearance but also contributes to overall upper body strength and functionality."
widget2:
  title: "Perfect 20 Mins Workout"
  url: "/twentymins-workout/"
  text: "This is the perfect workout combination for a quick 20 minutes burn, Get's you pumped and ready to conquer your day."
  video: '<iframe  height="250px" src="https://www.youtube.com/embed/iCQ2gC4DqJw" title="PERFECT 20 MIN FULL BODY WORKOUT FOR BEGINNERS (No Equipment)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>'
widget3:
  title: "The secret recipe for weight gain"
  url: "/weight-gain/"
  image: https://images.unsplash.com/photo-1581009146145-b5ef050c2e1e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTh8fGJvZHklMjBidWlsZGVyfGVufDB8fDB8fHww&auto=format&fit=crop&w=600&q=60
  text: "In a world often focused on weight loss, it's important to recognize that for some individuals, gaining weight can be just as challenging and important as shedding it."
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
  url: https://tinyletter.com/NessaKris
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/iCQ2gC4DqJw" title="PERFECT 20 MIN FULL BODY WORKOUT FOR BEGINNERS (No Equipment)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
