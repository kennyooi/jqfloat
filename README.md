jqfloat
=======

Create a Floating Effect on any object in your website, and make them come alive!

jqFloat.js is a jQuery plugin that able to make any HTML objects appear to be “floating” by binding a floating animation on the on it. 

Demo Page
=========

http://inwebson.com/demo/jqfloat/

How It Works
============

jqFloat.js uses jQuery .animate() method with infinity loop to animate object’s to random positions with random speed, thus make the object appears to be floating on the web page. Beside, it uses jQuery .data() method to store and keep track of each object’s attributes and status so that you can have multiple "floating" object on your website. 

Configuration
=============

	.jqFloat( [Method] [, Options] )
	
Methods
-------

- **Play** - Start floating animation.
- **Stop** - Start landing animation (stop floating animation).

Options
-------

- **width**	 - Maximum horizontal floating area. The value will be divided by 2 and append to object left and right. *(Default: 100)*
- **height** - Maximum vertical floating area. The value will be divided by 2 and append to object top and bottom. *(Default: 100)*
- **speed** - Maximum floating speed in Millisecond. *(Default: 1000)*
- **minHeight**	- The distance of floating object from bottom/surface. *(Default: 0)*




