---
title: "Deep Learning: Image Analysis Part 3 - Segmentation"
date: 2018-02-24T20:17:03Z
categories: ["deep-learning", "image-analysis"]
draft: true
---



### Understanding R-CNN

The goal of R-CNN is to take in an image, and correctly identify where the main objects (via a bounding box) in the image.

    * Inputs: Image
    * Outputs: Bounding boxes + labels for each object in the image.

But how do we find out where these bounding boxes are? R-CNN does what we might intuitively do as well - propose a bunch of boxes in the image and see if any of them actually correspond to an object.

The answer is [Selective Search](http://www.cs.cornell.edu/courses/cs7670/2014sp/slides/VisionSeminar14.pdf).


So, to summarize, R-CNN is just the following steps:

    * Generate a set of proposals for bounding boxes.
    * Run the images in the bounding boxes through a pre-trained AlexNet and finally an SVM to see what object the image in the box is.
    * Run the box through a linear regression model to output tighter coordinates for the box once the object has been classified.


### Understanding Fast R-CNN

### Understanding Faster R-CNN

### Understanding Mask R-CNN

### Understanding SSD
[Single Shot MultiBox Detector with Pytorch — Part 1](https://towardsdatascience.com/learning-note-single-shot-multibox-detector-with-pytorch-part-1-38185e84bd79)
