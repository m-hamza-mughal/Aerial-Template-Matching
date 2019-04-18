# Implementation of algorithm using Deep-Learning

This technique utilizes the Neighbourhood Consensus Networks to extract point to point correspondances between two images.
This project is in progress.

You will need to clone the official github repository of Neighbourhood Consensus Networks[1] for model.py to work. 
I have made modifications in the original model.py for my implementation.

Moreover, the code also uses SoftArgmax, for which I have used implementation of MWPainter[2]. You also will need that code (Link below)


## Requirements:
Python 3

Pytorch

Numpy

CUDA 9.0

OpenCV 

## References:
[1] Ignacio Rocco, Mircea Cimpoi, Relja Arandjelovic, Akihiko Torii, Tomas Pajdla, Josef Sivic,
“Neighbourhood Consensus Networks,” NeurIPS 2018

https://github.com/ignacio-rocco/ncnet

[2] MWPainter,
"SoftArgmax Implementation"

https://github.com/MWPainter/cvpr2019/blob/master/stitched/soft_argmax.py#L117


