slideforestslide
================

Just another slideshow jQuery plugin.

See the demo here: http://intergalacdev.net63.net/slideforestslide/

How to use it:

1. Copy and paste the code included in "index.html" file into the ".html" file in which you want the slideshow to be appeared.
2. The parameters of the plugin are the slideshow's width, height, transition time between the slides and the capability of doing this   
   transition manually or automatically. So if you want to have a slideshow with width 900px and height 300px, then in the code copied from index.html file change these lines as follows:

   <script>
		$(function(){
			$('#slides').slideforestslide({
				sliderWidth : 900, 
				sliderHeight : 300
			});
		});
   </script> 

   The parameters's name with their corresponding default values are: 
   		sliderWidth : 960,
        sliderHeight : 330,
        interTime : 3500,
        autoslideFlag: true

   So if you want let's say for example to change the transition time between the slides to 4 seconds (or 4000 in ms) and to change slides manually (with the existing buttons) then you have to write:

   <script>
		$(function(){
			$('#slides').slideforestslide({
				interTime : 4000,
				autoslideFlag: false
			});
		});
   </script> 

In conclusion you can change the header's name, the content of the paragraph on each slide and the corrensponding images, upon your needs.

Note: Influenced by an article of Jacob Gube. Find it here: http://sixrevisions.com/tutorials/javascript_tutorial/create-a-slick-and-accessible-slideshow-using-jquery/
