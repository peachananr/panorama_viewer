#Panorama Viewer by Pete R.
Embed interactive Panorama Pictures on your site with this simple plugin.
Created by [Pete R.](http://www.thepetedesign.com), Founder of [Travelistly](http://www.Travelistly.com) and [BucketListly](http://www.bucketlistly.com)

[![Panorama Viewer](http://www.thepetedesign.com/images/panorama_viewer_image.png "Panorama Viewer")](http://www.thepetedesign.com/demos/panorama_viewer_demo.html)

## Demo
[View demo](http://www.thepetedesign.com/demos/panorama_viewer_demo.html)

## Compatibility
Modern browsers such as Chrome, Firefox, and Safari on both desktop and smartphones have been tested. I have not tested this on IE.

## Basic Usage
You can now display your panorama photos on your site with this plugin. To do this, first you have to include the latest jQuery library together with `jquery.panorama_viewer.js` and `panorama_viewer.css` into your document's `<head>`. Now all you have to do this add your image to your HTML like this:


````html
<div class="panorama">
 <img src="your-panorama.jpg">
 ...
</div>
````

Make sure to change the source of the image to your image and call the function as shown below:

````javascript
  $(".panorama").panorama_viewer({
    repeat: false,              // The image will repeat when the user scroll reach the bounding box. The default value is false.
    direction: "horizontal",    // Let you define the direction of the scroll. Acceptable values are "horizontal" and "vertical". The default value is horizontal
    animationTime: 700,         // This allows you to set the easing time when the image is being dragged. Set this to 0 to make it instant. The default value is 700.
    easing: "ease-out",         // You can define the easing options here. This option accepts CSS easing options. Available options are "ease", "linear", "ease-in", "ease-out", "ease-in-out", and "cubic-bezier(...))". The default value is "ease-out".
    overlay: true               // Toggle this to false to hide the initial instruction overlay
  });
````

Now you will be able to display your panoramic photos without having to rely on the global width of the website. I hope you will find this useful. Stay tuned for more updates.

If you want to see more of my plugins, visit [The Pete Design](http://www.thepetedesign.com/#design), or follow me on [Twitter](http://www.twitter.com/peachananr) and [Github](http://www.github.com/peachananr).

## Other Resources
- [Tutorial](http://www.onextrapixel.com/2014/02/20/embed-an-interactive-panoramic-photo-with-jquery-panorama-viewer/)
