---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: index_page.jpg

#slider:
#text_color: white
#shadow_color: black
#slides: 
#  - image: gallery-example-1.jpg
#    slide_html:
#  - image: gallery-example-2.jpg
#    slide_html: "<h2>Yes, this carousel supports html texting</h2>"
#  - image: gallery-example-3.jpg
#    slide_html: "<h2>Yes, this carousel supports html texting</h2>"

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

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">

        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/gallery-example-1.jpg" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/gallery-example-2.jpg" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/gallery-example-3.jpg" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/gallery-example-4.jpg" alt="Slide 4" />
        </div>
    </div> 
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

## News
- Our lab homepage is now onine!
- We are hiring! Several Ph.D. positions available currently at USYD in computer vision. Please send to [this email address]('') for detailed information.

---
