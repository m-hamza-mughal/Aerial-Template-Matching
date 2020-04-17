# Deep Contextual Matching Based UAV Localization Using Semi-Local Constraints

Implementation code for the paper.
This project focuses on development of an algorithm for Template Matching on aerial imagery by implementing classical Computer Vision based techniques and deep-learning based techniques. This template matching technique is applied to extract GPS coordinates of the localized template image from the main image. 
This project primarily focuses on the problem of Vision-based Localization of Unmanned Aerial Vehicles.

![output_sift](https://github.com/m-hamza-mughal/Aerial-Template-Matching/raw/master/SIFT-based/output%20image.png)
## Classical Computer Vision based algorithm
This algorithm is implemented using SIFT[1] descriptors. 
The GPS coordinates are also extracted using GDAL functions. 

## Deep Learning based technique
This algorithm utilizes Neighbourhood Consensus Networks[2] presented in NeurIPS 2018 to extract point to point correspondances between two images. The correspondances are then used to match the template using Homography and RANSAC. The GPS coordinates are then extracted.

## References:
[1] David G Lowe, “Distinctive Image Features from Scale-Invariant Keypoints,” 
International Journal of Computer Vision, vol.50, No. 2,
2004, pp.91-110

[2] Ignacio Rocco, Mircea Cimpoi, Relja Arandjelovic, Akihiko Torii, Tomas Pajdla, Josef Sivic,
“Neighbourhood Consensus Networks,” NeurIPS 2018
