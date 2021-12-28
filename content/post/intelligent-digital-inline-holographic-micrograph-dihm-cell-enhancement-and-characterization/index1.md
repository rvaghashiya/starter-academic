---
title: Intelligent Digital Inline Holographic Micrograph (DIHM) Cell-Enhancement and Characterization
subtitle: 

active: false
# Summary for listings and search engines
summary:

# Link this post with a project
projects: []

# Date published
date: "2019-08-01"

# Date updated
lastmod: "2019-08-01"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin
- Dr. Mohendra Roy [(Assistant Professor, PDPU)](https://sites.google.com/view/mohendraroylab/home)

tags:
- Academic
- Research
- Deep Learning
- Pathology

categories:
- Demo
---

## Intelligent Digital Inline Holographic Micrograph (DIHM) Cell-Enhancement and Characterization

## Project Intro

Developing a novel and efficient neural model for detecting and classifying cells such as RBC, WBC, and cancer cells, etc.(cellular pathology) from DIH(Digital Inline Holographic) microscopy images

Implementation on a resource-constrained device to develop a cheap, reliable and portable point-of-care testing facility for diagnosis of pathological diseases, especially for usage in rural areas


## Highlights

- Segment cell-lines in DIH micrograph; performs signal enhancement using CNN-based autoencoder, followed by the cell-line characterization
- ROC-AUC: >0.98 for RBC, WBC, and microbeads; >0.88 for cancer cells HepG2 and MCF7
- Easy accommodation of newer cell-lines. Python, TensorFlow, OpenCV
- Preliminary work [published](https://ieeexplore.ieee.org/document/9374330) at the 8th IEEE ICHI 

{{< figure src="img1.png" title="Breast Cancer Disease Statistics" >}}

{{< figure src="img2.png" title="Limitations of Traditional Optic Microscopy" >}}


## Aim

The aim of the research is to create a
- Cheap,
- Reliable,
- Adaptable,
- Portable, and
- Intelligent
real-time point-of-care testing facility that could be used in resource-constrained environments, especially such as those in a rural setting.

{{< figure src="img3.png" title="" >}}

## Dataset

{{< figure src="cells.png" title="Cell-lines used in the project" >}}

## Current Progress

{{< figure src="img4.png" title="Cell-line EDA" >}}

The colored cell-lines is the result of EDA on the statistical properties and pixel intensity in the images

## Segmentation Results

{{< figure src="segmented_cells.png" title="The segmentation involves bit-plane splicing, adaptive thresholding, and contour approximation to crop the cell-lines" >}}


## CNN Model Performance

{{< figure src="confmatrix_with_acc_prevv.png" title="Confusion Matrix" >}}

The recognition performance of the CNN model on the augmented dataset

## Final Cell Counts for the Input Micrograph

{{< figure src="final_count.png" title="The final result in form of cell-counts for the ROI (region of interest) window selected in the DIH micrograph" >}}
