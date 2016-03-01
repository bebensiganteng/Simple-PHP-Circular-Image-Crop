Simple-PHP-Circular-Image-Crop
==============================

I've been looking for a solution to create a smooth circular image crop, but to my surprise it didn't exist!

You can use Image Magick to create something like this, but alas installing Image Magick is a huge hassle, ergo I'm using PHP GD since it's avalaible in most PHP library.

<h1>How to use</h1>
In the HTML divide the image size to half;
```html
 <!-- 
    Just divide the actual size to your liking
    width = 200px/2 = 100
    height = 100px/2 = 50
-->
<img src="image.php?path=sample.jpg" width="100" height="50">
```

Tested on 
- IE7 - IE10, Windows 8
- Chrome 25.0.1364.99
- Safari Version 6.0.2 (8536.26.17)
- Opera/9.80 (Macintosh; Intel Mac OS X 10.8.2) Presto/2.12.388 Version/12.14
- FF 18.0.2
- iPhone/iPad/Android (I forgot which version :p  ..will update later)

