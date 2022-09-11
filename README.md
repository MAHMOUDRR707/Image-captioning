# Image-captioning'

Image Captioning is a fascinating application of deep learning that has made tremendous progress in recent years. What makes it even more interesting is that it brings together both Computer Vision and NLP.

It takes an image as input and produces a short textual summary describing the content of the photo.

## About Dataset

## Context
A new benchmark collection for sentence-based image description and search, consisting of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events. … The images were chosen from six different Flickr groups, and tend not to contain any well-known people or locations, but were manually selected to depict a variety of scenes and situations

## Content66
What's inside is more than just rows and columns. Make it easy for others to get started by describing how you acquired the data and what time period it represents, too.

## Acknowledgements
We wouldn't be here without the help of others. If you owe any attributions or thanks, include them here along with any citations of past research.


## Architecture

The Architecture consist of Encoder and Decoder 

First we used for   extraction a pretrained model (VGG16) with removing the last   2 layers 

Encoder  has two inputs :

1 - for image feature  (DENSE)

2-  for  sequence feature  (LSTM)

Decoder with 2 layers (DENSE) with softmax activation function  on final layer with vocab size as umber of neurons

![Architecture](https://github.com/MAHMOUDRR707/Image-captioning/blob/master/download.png)

## Result

![res1](https://github.com/MAHMOUDRR707/Image-captioning/blob/master/res1.png)
![res2](https://github.com/MAHMOUDRR707/Image-captioning/blob/master/res2.png)
