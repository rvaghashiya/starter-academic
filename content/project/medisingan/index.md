---
title: MediSinGAN
subtitle: 

# Summary for listings and search engines
summary: An unconditional generative model to augment medical image datasets using a single natural image.


# Link this post with a project "MedisinGAN"
projects: [] 

# Date published
date: 2021-07-01T23:07:00.000Z

# Date updated
lastmod: "2020-09-01"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

tags:
  - Generative Networks
  - Medical Image Analysis
  - Computer Vision
  - Deep Learning
  - Research
  - Other

categories:
  - Demo

authors:
- admin
- Anagha Zachariah
- Ekaterina Nepovinnykh
- Phuc Nguyen
- Md.Sadek Hossain Asif
- Amrit Kumar Jethi
- Jonas Adler (Senior Research Scientist, DeepMind)

external_link: 

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  filename: ""
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: Smart
  preview_only: false
---

# MediSinGAN

The aim is to use an unconditional generative model, SinGAN, to augment medical image datasets using a single natural image.

## Current Progress

- Implemented SinGAN architecture in JAX for the generation of realistic synthetic medical imaging data using a
single training image and achieved a 20% reduction in training time
- Evaluated the model applicability in MRI cross-modality image-to-image translation, Synthetic brain tumor
generation, and Medical image segmentation (Histopathology)
