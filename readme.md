#Work in progress...

# ScratchCard
ScratchCard is a library javascript to generate scratch card (HTML5, canvas)
in modern browsers with touch events support.

## Options
- **canvasId :** Id string of canvas
- **imageBackground :** Path to background image
- **pictureOver :** Path to foreground image
- **sceneWidth :** Canvas width
- **sceneHeight :** Canvas height
- **radius :** Radius of clear zone 
- **nPoints :** Number of points generate inside the clear zone
- **pointSize :** { **x :** Number, **y :** Number } 
- **percent :** When clear the canvas after 'mouseup' event
- **callback :** Function executed after canvas clearing
- **cursor :** {  
	        **png :** // Path to the .png for modern browsers  
	        **x :** // Move position x  
	        **y :** // Move position y  
	        **cur :** // Path to the .cur for internet explorer  
    }

## Custom cusor for IE
```
<!--[if IE]> <html class="is-ie"> <![endif]-->
<!--[!(IE)]><!--> <html> <!--<![endif]-->
```