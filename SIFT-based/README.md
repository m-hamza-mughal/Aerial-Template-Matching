# Implementation of Algorithm using SIFT

The python notebook walks you through the algorithm and applies the algorithm to a video captured through UAV. 
A compressed output video is also given. 

The main image is in GeoTIFF Format. 
The GPS data of the Geo-TIFF is according to WGS-84 system.
You can see the information using following command in terminal.
```
gdalinfo 1.tif
```

The GPS coordinates of blue dot on main image are shown on left bottom corner of output frame.

## Requirements:

Numpy

OpenCV-Python 3.4.2.16

OpenCV-Contrib-Python 3.4.2.16

GDAL

Scipy

Matplotlib

