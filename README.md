# sticky-footer
A sticky footer, a critical part of your website navigation, "sticks" to the bottom of your browser window. This makes navigating your website easier and can be added with some CSS styles as shown below. In this article, [Solodev](https://www.solodev.com/) will provide you with the code needed to add a sticky footer to your website.

## Tutorial

For detailed instructions, view Solodev's [Adding a Sticky Footer Using CSS](https://www.solodev.com/blog/web-design/adding-a-sticky-footer-using-css.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/axbkbj77/)

## HTML

The sticky footer has the following HTML markup.

```
<footer class="ct-footer">
   <div class="container">
      <div class="ct-footer-meta text-center-sm">
         <div class="row">
            <div class="col-sm-6 col-md-2">
               <img alt="logo" src="images/logo.png">
            </div>
            <div class="col-sm-6 col-md-3">
               <address>
                  <span>WebCorpCo<br></span>123 Easy Street<br>
                  Orlando, Florida, 32801<br>
                  <span>Phone: <a href="tel:5555555555">(555) 555-8899</a></span>
               </address>
            </div>
            <div class="col-sm-6 col-md-2 ct-u-paddingTop10">
               <a href="" target="_blank"><img alt="app store" src="images/appstore.png"></a>
            </div>
            <div class="col-sm-6 col-md-2 ct-u-paddingTop10">
               <a href="" target="_blank"><img alt="google play store" src="images/androidstore.png"></a>
            </div>
            <div class="col-sm-6 col-md-3">
               <ul class="ct-socials list-unstyled list-inline">
                  <li>
                     <a href="" target="_blank"><img alt="facebook" src="images/facebook-white.png"></a>
                  </li>
                  <li>
                     <a href="" target="_blank"><img alt="twitter" src="images/twitter-white.png"></a>
                  </li>
                  <li>
                     <a href="" target="_blank"><img alt="youtube" src="images/youtube-white.png"></a>
                  </li>
                  <li>
                     <a href="" target="_blank"><img alt="instagram" src="images/instagram-white.png"></a>
                  </li>
                  <li>
                     <a href="" target="_blank"><img alt="pinterest" src="images/pinterest-white.png"></a>
                  </li>
               </ul>
            </div>
         </div>
      </div>
   </div>
   <div class="ct-footer-post">
      <div class="container">
         <div class="inner-left">
            <ul>
               <li>
                  <a href="">FAQ</a>
               </li>
               <li>
                  <a href="">News</a>
               </li>
               <li>
                  <a href="">Contact Us</a>
               </li>
            </ul>
         </div>
         <div class="inner-right">
            <p>
               Copyright © 2016 WebCorpCo.&nbsp;<a href="">Privacy Policy</a>
            </p>
            <p>
               <a class="ct-u-motive-color" href="" target="_blank">Web Design</a> by DigitalUs on <a href="" target="_blank">Solodev CMS</a>
            </p>
         </div>
      </div>
   </div>
</footer>
</div>
</footer>
```

## CSS

All necessary CSS is included in sticky-footer.css

## External Includes

This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="sticky-footer.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
