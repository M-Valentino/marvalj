# MarvalJ
MarvalJ was created as a fork of MarvinJ which hasn't been updated in four years. MarvalJ aims to expand upon the features MarvinJ has, as well as improving performance.

## Running
You can download the JavaScript file and import it into the HTML body of a webpage like so:

```
<body>
  <script src="marvalj_0.2.js"></script>
  ....
</body>

```
## Documentation
All functions and variables in MarvalJ are the same as MarvinJ with the exception that all instances of "Marvin" or "marvin" are "Marval" or "marval".

MarvalJ has four functions that MarvinJ doesn't have.

### Marval.blackAndWhiteNoise(imageIn, imageOut, intensity)	
Given an input image imageIn, an output image imageOut and an intensity, applies random black and white noise to pixels. intensity has a range of 0 to 1.0.

### Marval.colorNoise(imageIn, imageOut, intensity)	
Given an input image imageIn, an output image imageOut and an intensity, applies random color noise to pixels. intensity has a range of 0 to 1.0.

### Marval.horizontalScanLines(imageIn, imageOut, intensity)
Given an input image imageIn, an output image imageOut and an intensity, applies horizontal scan lines to the image. intensity has a range of 0 to 255.

### Marval.verticalScanLines(imageIn, imageOut, intensity)
Given an input image imageIn, an output image imageOut and an intensity, applies vertical scan lines to the image. intensity has a range of 0 to 255.

See MarvinJ's documentation:
https://www.marvinj.org/en/algorithms.html
