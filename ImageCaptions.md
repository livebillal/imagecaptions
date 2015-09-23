# Introduction #

Image captions adds dynamic captions to images using jquery.
This is my first plug-in and is more of a proof of concept then production code so use it at your own discretion.
I have tested it using Firefox 2.0.0.14, IE 7, Opera 9.50 beta and safari 3.1.1.

# Details #

you can view a [Demo](http://homegel.co.za/imagecaption/) here which has various examples.

I'm still new at this so any feedback will be most welcome as well as any advice on how to improve the code. I do have some ideas already but will love the feedback.

Sample Code:

```
$(document).ready(function(){
	$('.captionImage1').imageCaption({
		toCaption: 'captionImage1',
		motionIn: 'easeInOutSine',
		motionOut: 'easeInOutSine',
		speedIn: 300,
		speedOut: 300,
		textColor: '#fff',
		captionBoxColor: '#000',
		captionTipColor: '#000',
		captionBoxOpacity: '0.6',
		captionTipOpacity: '0.6',
		autoHide: true
	});
});");
```