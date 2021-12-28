---
title: "Smart, Portable, and Cost-effective ELISA Reader"
subtitle: 

# Summary for listings and search engines
summary:   A microplate well segmentation pipeline for real-time colorimetric analysis of microplate wells.

# Date published
date: 2020-09-01T20:52:00.000Z

# Date updated
lastmod: "2020-09-01"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

authors:
- admin
- Dr. Abhijit Roy (Assistant Professor, IISc)
- Dr. Mohendra Roy (Assistant Professor, PDPU)

tags:
  - Machine Learning
  - Image Segmentation
  - Colorimetry Analysis
  - Research
  - Academic
  - ELISA

<!-- categories:
- Demo
 -->
 
external_link: 

# Link this post with a project [smart-portable-and-cost-effective-elisa-reader]
projects: [] 

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  filename: elisa_plate.jpg
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: Smart
  placement: 2
  preview_only: false
---

## Project Goals

- Cost-effective and portable ELISA reader with AI-aided analyzer and adaptive calibration
- Image processing based qualitative and quantitative real-time analysis

## Current Progress

- Completed precise micro-plate well localization
- Well localization utilizes bit plane slicing, masking and contouring, and shape appropriation
- Extracts basic color information, measuring light intensity in RBG colorspace, for each well
- Provides normalized measure of intenstity

### Note

- Uses standard well-reference: A-H for rows, 1 to 12 for columns
- ‘00’ for base/reference well

Sample: Segmented Microplate-wells (Pic shows a zoomed section of the microplate)
{{< figure src="contoured_img.png" title="Sample: Segmented Microplate-wells (Pic shows a zoomed section of the microplate)" >}}

Locations of Segmented Wells
{{< figure src="well_data.png" title="Locations of Segmented Wells" >}}

| | |
| --- | ---|
| {{< figure src="45well.png" title="A cropped Well filled with a solution" >}} | {{< figure src="56well.png" title="A cropped empty Well" >}} |
 
Well boundary colored has been colored for reference in the above figures.

### Note:
Full work till date cannot be disclosed
