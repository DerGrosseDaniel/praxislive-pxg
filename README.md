# praxislive-pxg
Here are my custom pxgs and nice ones from other people

## core patches

* `sin.pxg`
Gnerates values on sinus curve. Speed is adjustable, as are minimum and maximum.

* `pwm.pxg`
Pulses value with a given duty cycle.

## video patches

* `colSeparator.pxg`
seperates rgb-channels to the left and right, you have amount and scale as input. 1 amount is 1% leftright and scale is multiplied by it.

* `fft.pxg`
GPL code ported from Beads http://www.beadsproject.net (c) Holger Crysandt / Ollie Bown
creates array with half the number floats of audioblock size elementes with lowest to highest frequencies

* `vibrancy.pxg`
change vibrancy of image, adapted from https://www.interactiveshaderformat.com/sketches/282

* `rgbHalftone.pxg`
created halftone pattern, adapted from msfeldsteins shader https://www.interactiveshaderformat.com/sketches/20

* `edgeDetection.pxg`
classic edge detection like the name says.

* `LumaKey.pxg`
Luminance key for video input. Sets the alpha channel to 0 if pixel is brighter or darker than corresponding threshold. If show-matte is checked, the image is black and white and shows alpha channel on all channels (alpha is solid on in this case).

* `invert.pxg`
Inverts all channels (not the alpha channel).

* `setChannels.pxg`
You can switch channels to others with this patch. For example if "red-to-red" is checked the red channel of the input is copied to the red chennel of the output. If the "green-to-red" is checked too, the green channel is added to that as well.

* `color.pxg`
generates color either with rgb values or hsv values.

* `randomCircles.pxg`
generates random circles on Screen

* `threeCircles.pxg`
generates 3 fully customizable circles with following options:
  * `c-x-edit`if theis is checked, then you can set position of circle in the video via mouse click
  * `c-x-circle`if checked it links width and heigh of circle, if not checked both can be edited independent
  * `c-x-mix-y-achse` mirrors circle horizontan and/or vertically
  * the rest should be obvious :)
  
* `Adder10x.pxg`
add 10 video layers. Each is individual switchable.

* `maskMix.pxg`
Mixes two input images according to a third mask image. If the mask pixel perceived brightness is 100% the white image will be choosen, if it is 0% the black image. Grey pixel values are mixed accordingly.

* `bitDepth.pxg`
Reduces the number of possible colors by rounding the color to the nearest color.

* `pixelate.pxg`
Pixelates image. To speedup processing only one pixel of the source image is sampled per bigger pixel, so you ironically may not get the disired resolution out of this low resolution filter.

* `gain.pxg`
This is a video gain. You can increase and decrease brightness of video. Very handy for feedbackloops to lessen impact. Really nice with edge detection.

* `valPlot.pxg`
Plots inputvalue as white line on black background. Very good for debugging.
