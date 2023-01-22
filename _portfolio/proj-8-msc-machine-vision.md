---
title: "Apple counting using Machine Vision"
excerpt: "MSc Course Project - EMATM0056 Machine Vision"
collection: portfolio
---


Group Project:
======

ABSTRACT
It is crucial to have an accurate and reliable image-based fruit detection system to
support more hierarchical agricultural tasks such as yield mapping and Robo-Harvest.
This project applies the Minneapple dataset instead of physical data collection experiments,
and designs, implements and evaluates the use of conventional image
processing based apple counting methods and an advanced object detection framework
Mask R-CNN for orchard apple detection. In particular, Mask R-CNN replaces
RoI Pooling with RoIAlign and adds a branch in the classifier stage for removing the
mask of the object, which solves the problem of inconsistency between the candidate
and ground truth boxes caused by RoI Pooling using two integerizations. In terms of
apple detection results the conventional image processing method is able to identify
most of the apples in the image, but is unable to distinguish apples on the ground from
those on the trees; Mask R-CNN is able to identify more accurately through extensive
training, and performs well even on highly obscured fruit. The mean accuracy of the
conventional image processing method is calculated to be 45.5%, while the mean
accuracy of Mask R-CNN is 59%.

Keywords: Machine vision, Minneapple dataset, Image processing, Conventional
image processing, Deep learning, Mask R-CNN
