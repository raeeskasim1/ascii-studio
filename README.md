# ASCII Studio

Turn a local image into text art, or generate a sample pattern. Everything happens inside your browser.


## Try it

https://raeeskasim1.github.io/ascii-studio/

Try the sample, move the column slider, invert brightness, then load a local photo and save the text art.

## How it works

Canvas downsamples an uploaded image, calculates luminance, and maps brightness to a character ramp. Row count accounts approximately for the character aspect ratio. Uploaded images are decoded locally and are never sent to a server. Export is plain text. This is image processing, not a trained computer-vision model.
