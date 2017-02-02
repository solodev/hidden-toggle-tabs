# hidden-toggle-tabs
Your homepage needs to display your core offerings in a way that website visitors see it immediately. Whether you are a product or service company, your core products and/or services need to have the most prominence on your homepage. 

While your hero is reserved for your big picture marketing messages, directly below you need to visually display your offerings in a graphical and interactive way. Using toggled tabs to display these offerings allows you to save real estate on your web page as details for a particular product or service only appear on click. In this article, [Solodev](https://www.solodev.com/) will show you how to add togggled tabs to your website.

## Tutorials

For detailed instructions, view Solodev's [How to Add Hidden Toggle Tabs to your Homepage](https://www.solodev.com/blog/web-design/how-to-add-hidden-toggle-tabs-to-your-website.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/cz1q9s3p/).

## HTML

The hidden toggle tabs contain the following basic markup.
```
<section class="container">
        <h2 class="ct-pageHeader text-center">
           The WebCorpCo Product Suite
        </h2>
        <p class="paddingBottom45 text-center">
           WebCorpCo sells it all. You name it - we sell it.<br>
           From precious diamonds and airplanes to a refreshing cup of coffee, we've got your back.
        </p>
        <div class="ct-tabs-outer js-tabs">
           <div class="row text-center">
                  <div class="col-md-2 col-sm-2 col-xs-4">
                         <div class="item v_associations" data-link="#" data-tab="associations">
                                <div class="inner">
                                   &nbsp;
                                   <i class="fa fa-book" aria-hidden="true"></i>
                                </div>
                                <h2>
                                   Books
                                </h2>
                         </div>
                  </div>
                  <div class="col-md-2 col-sm-2 col-xs-4">
                         <div class="item v_education" data-link="#" data-tab="education">
                                <div class="inner">
                                   &nbsp;
                                   <i class="fa fa-coffee" aria-hidden="true"></i>
                                </div>
                                <h2>
                                   Coffee
                                </h2>
                         </div>
                  </div>
                  <div class="col-md-2 col-sm-2 col-xs-4">
                         <div class="item v_entertainment" data-link="#" data-tab="entertainment">
                                <div class="inner">
                                   &nbsp;
                                   <i class="fa fa-diamond" aria-hidden="true"></i>
                                </div>
                                <h2>
                                   Diamonds
                                </h2>
                         </div>
                  </div>
                  <div class="col-md-2 col-sm-2 col-xs-4">
                         <div class="item v_finance" data-link="#" data-tab="finance">
                                <div class="inner">
                                   &nbsp;
                                   <i class="fa fa-gamepad" aria-hidden="true"></i>
                                </div>
                                <h2>
                                   Gaming
                                </h2>
                         </div>
                  </div>
                  <div class="col-md-2 col-sm-2 col-xs-4">
                         <div class="item v_government" data-link="#" data-tab="government">
                                <div class="inner">
                                   &nbsp;
                                  <i class="fa fa-plane" aria-hidden="true"></i>
                                </div>
                                <h2>
                                   Airplanes
                                </h2>
                         </div>
                  </div>
                  <div class="col-md-2 col-sm-2 col-xs-4">
                         <div class="item v_healthcare" data-link="#" data-tab="healthcare">
                                <div class="inner">
                                   &nbsp;
                                   <i class="fa fa-motorcycle" aria-hidden="true"></i>
                                </div>
                                <h2>
                                   Motorcycles
                                </h2>
                         </div>
                  </div>
           </div>
           <!-- / row -->
        </div>
        <!-- / ct-tabs-outer -->
        <div class="ct-tab-container">
          <div class="ct-tab-content v_associations" data-tab="associations">
                <div class="inner">
                  <button class="widget-close js-closeSection">&times;</button>
                  <div class="row">
                        <div class="col-xs-6"><img alt="Manufacturing Icon" src="https://www.solodev.com/assets/industries/engineering-content-tab.jpg" /></div>
                        <div class="col-xs-6 v_manufacturing_description">
                          <h4>WORDS WORDS WORDS</h4>
                          <p>We've got stacks of books for days. You want a book? We've got you. Just pick a book, buy it, and download it to your PC or mobile device. It's that easy.</p>
                          <br />
                          <a class="btn btn-darkred ct-u-size18" href="#">Learn more<img alt="White Arrow" src="https://www.solodev.com/assets/industries/right-white.png" /></a>
                        </div>
                  </div>
                </div>
          </div>
          <div class="ct-tab-content v_education" data-tab="education">
                <div class="inner">
                  <button class="widget-close js-closeSection">&times;</button>
                  <div class="row">
                        <div class="col-xs-6"><img alt="Education Icon" src="https://www.solodev.com/assets/industries/education-tab-content.jpg" /></div>
                        <div class="col-xs-6 v_education_description">
                          <h4>WAKE UP AND SMELL THE COFFEE</h4>
                          <p>Don't have time to make coffee at home or pick some up on the way to work? No problem, we offer a 24/7 coffee delivery service that gets the right coffee in the right hands at the right time.</p>
                          <br />
                          <a class="btn btn-lightblue ct-u-size18" href="#">Learn more<img alt="White Arrow" src="https://www.solodev.com/assets/industries/right-white.png" /></a>
                        </div>
                  </div>
                </div>
          </div>
          <div class="ct-tab-content v_entertainment" data-tab="entertainment">
                <div class="inner">
                  <button class="widget-close js-closeSection">&times;</button>
                  <div class="row">
                        <div class="col-xs-6"><img alt="Media Icon" src="https://www.solodev.com/assets/industries/media-content-tab.jpg" /></div>
                        <div class="col-xs-6 v_media_description">
                          <h4>DIAMONDS ARE FOR NOW</h4>
                          <p>Forget waiting "forever" for your diamonds. Feel like getting your hands on some crystal clear diamonds from the exotic lands of Imagibu? Pick your diamond of choice and you'll have it within the hour!</p>
                          <br />
                          <a class="btn btn-lightorange ct-u-size18" href="#">Learn more<img alt="White Arrow" src="https://www.solodev.com/assets/industries/right-white.png" /></a>
                        </div>
                  </div>
                </div>
          </div>
          <div class="ct-tab-content v_finance" data-tab="finance">
                <div class="inner">
                  <button class="widget-close js-closeSection">&times;</button>
                  <div class="row">
                        <div class="col-xs-6"><img alt="Finance Icon" src="https://www.solodev.com/assets/industries/finance-tab-content.jpg" /></div>
                        <div class="col-xs-6 v_finance_description">
                          <h4>WE'RE GAMERS</h4>
                          <p>Name a game console. We sell it. Not only do we sell it, we fix them, we deliver them, we pick them up, and we have everything you need to have the coolest gaming setup ever. Awesome!</p>
                          <br />
                          <a class="btn btn-lightgreen ct-u-size18" href="#">Learn more<img alt="White Arrow" src="https://www.solodev.com/assets/industries/right-white.png" /></a>
                        </div>
                  </div>
                </div>
          </div>
          <div class="ct-tab-content v_government" data-tab="government">
                <div class="inner">
                  <button class="widget-close js-closeSection">&times;</button>
                  <div class="row">
                        <div class="col-xs-6"><img alt="Retail Icon" src="https://www.solodev.com/assets/industries/retail-content-tab.jpg" /></div>
                        <div class="col-xs-6 v_retail_description">
                          <h4>AIRPLANES READY TO GO!</h4>
                          <p>Sometimes after a long day of work, we all need a little airplane. Feel like a quick trip to the Galapagos or Bahamas? Simply rent one of our airplanes and you'll be back just in time for work the next morning!</p>
                          <br />
                          <a class="btn btn-purple ct-u-size18" href="#">Learn more<img alt="White Arrow" src="https://www.solodev.com/assets/industries/right-white.png" /></a>
                        </div>
                  </div>
                </div>
          </div> 
          <div class="ct-tab-content v_healthcare" data-tab="healthcare">
                <div class="inner">
                  <button class="widget-close js-closeSection">&times;</button>
                  <div class="row">
                        <div class="col-xs-6"><img alt="Healthcare Icon" src="https://www.solodev.com/assets/industries/healthcare-tab-content.jpg" /></div>
                        <div class="col-xs-6 v_healthcare_description">
                          <h4>MOTORCYCLES ON DEMAND</h4>
                          <p>We all need a quick getaway or a rush of adrenaline every once in a while. Reserve a motorcycle, pick a time and place and it'll be delivered right to you. *Insurance Required</p>
                          <br />
                          <a class="btn btn-darkblue ct-u-size18" href="#">Learn more<img alt="White Arrow" src="https://www.solodev.com/assets/industries/right-white.png" /></a>
                        </div>
                  </div>
                </div>
          </div>
        </div>
</section>
```
## CSS

All required CSS is in the file product-tabs.css

## JavaScript

This tutorial utilizes the JavaScript below.
```
$(document).ready(function () {
  $('.js-tabs .item').click(function() {
    var $this = $(this);
    $tab_content = $('.ct-tab-content');
    $el_tab = $('.js-tabs .item');

      var target;
      target = $this.attr('data-tab');
      if (!$this.hasClass('active')) {
        $el_tab.removeClass('active');
        $tab_content.removeClass('active');
        $this.addClass('active');
        return $('.ct-tab-content[data-tab="' + target + '"]').addClass('active');
      } else {
        $this.removeClass('active');
        return $tab_content.removeClass('active');
      }
  });

  $('.js-closeSection').click(function() {
    var $this = $(this);
    $(".ct-tabs-outer .item").removeClass("active");
    $this.closest(".ct-tab-content").removeClass("active");
  });
});

```

## External Includes

This tutorial utilizes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
<link href="product-tabs.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="product-tabs.js"></script>
```
