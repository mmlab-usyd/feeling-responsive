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

sidebar: right

widget1:
  title: "Research 1"
  url: '#'
  image: widget-1-302x182.jpg
  text: 'Our research about xxxxxxxxxxxxxxxxxxxxxxxxx <br/> is already online!'
widget2:
  title: "Research 2"
  url: '#'
  text: 'our research about xxxxxxxxxxxxxxxxxxxxxxx <br/> is already online!'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Our Research 3"
  url: '#'
  image: widget-github-303x182.jpg
  text: 'our research about xxxxxxxxxxxxxxxxxxxxxxx <br/> is already online!'

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

<!-- Logo & header -->
<div class="row" style="margin-top: 15px">
  <div class="column small-2">
    <img src="assets/img/favicon-usyd.png" width="120" height="128">
  </div>
  <div class="column small-10">
    <div class="row">
      <h1> Multimedia Laboratory </h1>
    </div>
    <div class="row">
      <h2> The University of Sydney</h2>
    </div>
  </div>
    
</div>

--- 

<div class="row main-content">
  <div class="column small-9">
    
    <!-- carrousel -->

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
            <a href="#">
              <img src="images/gallery-example-1.jpg" alt="Los Angeles" style="width:100%;">
              <div class="carousel-caption d-none d-md-block">
                <h3 style="color: #FFFFFF"> First Image</h3>
                <p> caption for the first image. </p>
              </div>
            </a>
          </div>

          <div class="item">
            <a href="#">
              <img src="images/gallery-example-2.jpg" alt="Chicago" style="width:100%;">
              <div class="carousel-caption d-none d-md-block">
                <h3 style="color: #FFFFFF"> Second Image</h3>
                <p> caption for the second image.</p>
              </div>
            </a>
          </div>
        
          <div class="item">
            <a href="#">
              <img src="images/gallery-example-3.jpg" alt="New york" style="width:100%;">
              <div class="carousel-caption d-none d-md-block">
                <h3 style="color: #FFFFFF"> Third Image</h3>
                <p>caption for the third image. </p>
              </div>
            </a>
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
  </div>
  <div class="column small-3">
    <h3>News</h3>
    <div class="list-group" style="margin-left=0">
      <button class="list-group-item list-group-item-action">
        <span class="badge badge-default badge-pill">14-Dec-2017</span>
        Our lab homepage is now onine!
      </button>
      <button class="list-group-item list-group-item-action">
        <span class="badge badge-default badge-pill">14-Dec-2017</span>
        We are hiring! Several Ph.D. positions are now available at USYD in computer vision. Candidates with strong academic background and/or solid programming skill are preferred. If you are interested, please send your CV to <a href="mailto:wanli.ouyang@sydney.edu.au"><strong>this email address</strong></a> for further information.
      </button>
    </div>
  </div>
</div>

---
