# droplet_image_analysis
This code analyses AVI video files by binarizing each frame and picking out a droplet using a pixel intensity threshold.
Analysis of this shape results in output data such as aspect ratio, volume, contact angle and surface area with time.


For single images, 'My droplet finder' should be adequate to calculate area (in pixels) and some other basic droplet shape/size data.
There is currently no output file for this vi, as I mainly use it to calculate droplet area data which I collate elsewhere.


For AVI videos, 'HFRI droplet analysis' should be used. This is a more complex analysis program (HFRI = high frame rate imaging) as these
are the videos I collect, but any frame rate videos can be analysed. This program also has a pixel/micron scale input, so add your known
scale here to output meaningful data.