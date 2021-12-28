---
title: DIH-Cell-Augmentor
subtitle: 

# Summary for listings and search engines
summary: Cell-line image augmentation for biological cells captured via Digital Inline Holographic Microscopy.

# Date published
date: 2020-08-01T23:09:00.000Z

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

tags:
  - DIH Microscopy
  - Image Data Augmentation
  - Other

categories:
  - Demo

authors:
  - admin
  - Dr. Mohendra Roy (Assistant Professor, PDPU)

external_link: 

# Link this post with a project "intelligent-digital-inline-holographic-micrograph-dihm-cell-enhancement-and-characterization"
projects: [] 

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  filename: dih.jpg
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: Smart
  preview_only: false
---

# DIH-Cell-Augmentor
A setup for augmentation of biological cells captured via Digital Inline Holography

## Aim
  * A script to augment the cell-lines obtained via DIHM.
  * It generates rotated copies of the input cell sample, while maintaining the same image dimensions and near-similar sample background, using OpenCV.
  * The augmented samples preserve the spatial features as well as the statistical distribution present in the input sample.

## Method
* Load dataset, having images grouped under labels
* Augment cell sample by rotation at specific angle
* Store augmented images in a csv

## Augmentation Procedure
* Create a mask to extract the cell background
* Negate the above mask to extract the cell 
* Rotate the image by specified degree, achieved via `getRotationMatrix2D` and `warpAffine` functions in cv2
* Extract the rotated cell signature using the negated mask
* Mask it with the extracted cell background to create an augmented image, with same shape as original image

Note: The code is applicable only for augmentation of objects/cells lying within the maximum fitting circle which can be fit into the image

## Pre-requisites:
* cv2
* glob, or alternatively use os
* numpy

## Demo:

### Input Image: 
<img src="images/original.jpg" width=100 >

### Augmented Images:
Augmented Images on rotation by 0, 10, 20, 30,.....,350 degrees :

| <!-- -->  | <!-- -->  | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
|------------|-------------|----------|----------|----------|----------|
| <img src="images/aug_img_0.jpg" width=100 >  | <img src="images/aug_img_40.jpg" width=100 > | <img src="images/aug_img_80.jpg" width=100 > | <img src="images/aug_img_120.jpg" width=100 > | <img src="images/aug_img_160.jpg" width=100 > | 
| <img src="images/aug_img_200.jpg" width=100 > | <img src="images/aug_img_240.jpg" width=100 > | <img src="images/aug_img_280.jpg" width=100 > | <img src="images/aug_img_320.jpg" width=100 > | <img src="images/aug_img_350.jpg" width=100 > |

Note: Black dot has been added for easier vizualization

[Git: DIH Cell Augmentor](https://github.com/raj-98/DIH-Cell-Augmentor)
