# praxislive-pxg
Here are my custom pxgs and nice ones from other people

## colSeparator.pxg
seperates rgb-channels to the left and right, you have amount and scale as input. 1 amount is 1% leftright and scale is multiplied by it.

## fft.pxg
Custom FFT component sends
frequency data to video patch.
GPL code ported from Beads
http://www.beadsproject.net
(c) Holger Crysandt / Ollie Bown

creates array with half the number floats of audioblock size elementes with lowest to highest frequencies

## vibrancy.pxg
change vibrancy of image
adapted from zoidbergs code https://www.interactiveshaderformat.com/sketches/282

## rgbHalftone.pxg
created halftone pattern
adapted from msfeldsteins shader https://www.interactiveshaderformat.com/sketches/20

## edgeDetection.pxg
classic edge detection like the name says.

## LumaKey.pxg
Luminance key for video input. Sets the alpha channel to 0 if pixel is brighter or darker than corresponding threshold. If show-matte is checked, the image is black and white and shows alpha channel on all channels (alpha is solid on in this case).

## invert.pxg
Inverts all channels (not the alpha channel).

## setChannels.pxg
You can switch channels to others with this patch. For example if "red-to-red" is checked the red channel of the input is copied to the red chennel of the output. If the "green-to-red" is checked too, the green channel is added to that as well.
