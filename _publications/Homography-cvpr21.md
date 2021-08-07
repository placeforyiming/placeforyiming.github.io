---
title: "Deep Lucas-Kanade Homography for Multimodal Image Alignment"
collection: publications
permalink: /publications/Homography-cvpr21
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2021-07-22
venue: "International Conference on Computer Vision 2021"
paperurl: ""
citation: '<b>Yiming Zhao</b>, Xinming Huang, Ziming Zhang. "Deep Lucas-Kanade Homography for Multimodal Image Alignment". <i>CVPR</i>. 2021.'
---
# Deep Lucas-Kanade Homography for Multimodal Image Alignment

## Abstract
Estimating homography to align image pairs captured by different sensors or image pairs with large appearance changes is an important and general challenge for many computer vision applications. In contrast to others, we propose a generic solution to pixel-wise align multimodal image pairs by extending the traditional Lucas-Kanade algorithm with networks. The key contribution in our method is how we construct feature maps, named as deep Lucas-Kanade feature map (DLKFM). The learned DLKFM can spontaneously recognize invariant features under various appearance-changing conditions. It also has two nice properties for the Lucas-Kanade algorithm: (1) The template feature map keeps brightness consistency with the input feature map, thus the color difference is very small while they are well-aligned. (2) The Lucas-Kanade objective function built on DLKFM has a smooth landscape around ground truth homography parameters, so the iterative solution of the Lucas-Kanade can easily converge to the ground truth. With those properties, directly updating the Lucas-Kanade algorithm on our feature maps will precisely align image pairs with large appearance changes. We share the dataset, code, and demo video online.
