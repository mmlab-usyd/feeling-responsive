---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth:
title: "Multimedia Lab @ USYD"

slider:
text_color: white
shadow_color: black
slides: 
  - image: gallery-example-1.jpg
    slide_html:
  - image: gallery-example-2.jpg
    slide_html: "<h2>Yes, this carousel supports html texting</h2>"
  - image: gallery-example-3.jpg
    slide_html: "<h2>Yes, this carousel supports html texting</h2>"

sidebar: right

widget1:
  title: "Research 1"
  url: '#'
  image: widget-1-302x182.jpg
  text: 'Our research about xxxxxxxxxxxxxxxxxxxxxxxxx'
widget2:
  title: "Research 2"
  url: '#'
  text: 'our research about xxxxxxxxxxxxxxxxxxxxxxx <br/>'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Our Research 3"
  url: '#'
  image: widget-github-303x182.jpg
  text: 'our research about xxxxxxxxxxxxxxxxxxxxxxx <br/> is already online'

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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

## Multimedia Lab
####     The University of Sydney


<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner">
      <div class="item active">
        <img src="images/gallery-example-1.jpg" alt="Los Angeles" style="width:100%;">
      </div>

      <div class="item">
        <img src="images/gallery-example-2.jpg" alt="Chicago" style="width:100%;">
      </div>
    
      <div class="item">
        <img src="images/gallery-example-3.jpg" alt="New york" style="width:100%;">
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
</div>


## News
- Our lab homepage is now onine!
- We are hiring! Several Ph.D. positions are now available at USYD in computer vision. Students with strong academic background and/or awesome programming skill are preferred. If you are interested,  please send your CV to [this email address]("mailto:wanli.ouyang@sydney.edu.au") for further information.

---
