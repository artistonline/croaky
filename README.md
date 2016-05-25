# croaky
a smattering of html, css and js

********************************
CSS Check Mark**
#mainContainer .included-list .check {
    border-bottom: 2px solid #aaaab2;
    border-right: 2px solid #aaaab2;
    float: left;
    height: 16px;
    margin-left: 1.25em;
    position: relative;
    top: 2px;
    transform: rotate(45deg);
    width: 7px;

***************************
Pie**
	border: 1px solid #cc9c52;
	-webkit-border-radius: 5px 5px 1px 1px;
-moz-border-radius: 5px 5px 1px 1px;
border-radius: 5px 5px 1px 1px;
-webkit-box-shadow: #666 0px 2px 3px;
-moz-box-shadow: #666 0px 2px 3px;
box-shadow: #666 0px 2px 3px;
	background: #F4ECE0;
background: -webkit-gradient(linear, 0 0, 0 bottom, from(#F4ECE0), 

to(#FFFFFF));
background: -webkit-linear-gradient(#F4ECE0, #FFFFFF);
background: -moz-linear-gradient(#F4ECE0, #FFFFFF);
filter:  progid:DXImageTransform.Microsoft.gradient

(startColorStr='#F4ECE0', EndColorStr='#FFFFFF'); /* IE6,IE7 */
-ms-filter: "progid:DXImageTransform.Microsoft.gradient

(startColorStr='#F4ECE0', EndColorStr='#FFFFFF')"; /* IE8 */
background: -ms-linear-gradient(#F4ECE0, #FFFFFF);
background: -o-linear-gradient(#F4ECE0, #FFFFFF);
11:58 AM 5/23/2013
-pie-background: linear-gradient(#F4ECE0, #FFFFFF);


********************
Top**

<a id="top">
 <a href="#top" class="top">back to top</a>  

 
*******************
Feedburner**

 <script src="http://feeds.feedburner.com/AscMedia?format=sigpro" 

type="text/javascript" ></script><noscript><p>Subscribe to RSS 

headline updates from: <a 

href="http://feeds.feedburner.com/AscMedia"></a><br/>Powered by 

FeedBurner</p> </noscript>

<link href='http://fonts.googleapis.com/css?family=Noto

+Sans:400,700|Ubuntu+Condensed|Karla:400,700|Open+Sans:400,600,700' 

rel='stylesheet' type='text/css'>

<link rel="stylesheet" type="text/css" href="/css/lctest.css">


********************
Expand View**

    <script type="text/javascript"> $(document).ready(function() { 

$('div.view6').hide(); $('div.slide6').toggle(function() { 

$(this).siblings('div.view6').fadeIn('slow'); }, function() { 

$(this).siblings('div.view6').fadeOut('fast'); return false; }); 

}); </script>
    <div id="newsItem">
      <p></p>
      <div class="slide6" style="cursor: pointer;"><span>Read More 

»</span></div>
      <div class="view6">
        <p></p>
      </div>
