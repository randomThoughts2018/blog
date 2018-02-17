---
title: "Deep Learning: Image Analysis Part 1 - Classification"
date: 2018-02-17T20:17:03Z
categories: ["deep-learning", "image-analysis"]
draft: true
---

## Introduction 

## Build the model 

## Imroving the model 

### Data Augmentation 

### Finetuning and Differential Learning Annealing 

## 7 Steps to build a world-class image classifier 
* Enable data augmentation, and ```precompute=True```
* Use ```lr_find()``` to find highest learning rate where loss is still clearly improving
* Train last layer from precomputed activations for 1-2 epochs
* Train last layer with data augmentation (i.e. ```precompute=False```) for 2-3 epochs with ```cycle_len=1```
* Unfreeze all layers.
* Set earlier layers to 3x-10x lower learning rate than next higher layer.
* Use ```lr_find()``` again.
* Train full network with ```cycle_mult=2``` until over-fitting.

