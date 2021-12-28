---
title: People Counter App
subtitle: 

# Date published
date: 2020-06-25T22:50:00.000Z

# Summary for listings and search engines
summary: OpenVINO-based Person detection and monitoring app to detect people in a designated area and deliver statistics based on the same.

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

tags:
  - OpenVINO
  - Image Analytics
  - People Counter
  - Deep Learning
  - Edge AI
  - Other

categories:
  - Demo

# Link this post with a project "intelligent-digital-inline-holographic-micrograph-dihm-cell-enhancement-and-characterization"
projects: [] 

authors:
- admin

external_link: 

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  filename: people-counter-image.png
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: Smart
  preview_only: false
---

# Deploy a People Counter App at the Edge

| Details            |              |
|-----------------------|---------------|
| Programming Language: |  Python 3.5 or 3.6 |

![people-counter-python](./people-counter-image.png)

## What it Does

The people counter application will demonstrate how to create a smart video IoT solution using Intel® hardware and software tools. The app will detect people in a designated area, providing the number of people in the frame, average duration of people in frame, and total count.

## Aim

 * Create an app that will help maintain social distancing at public places likes grocery stores and shopping malls, to curb the spread of Covid-19 virus
 * The app will detect people in a designated area, providing the number of people in the frame, average duration of people in frame, and total count.
 * The people counter application is a smart video IoT solution based on Intel® hardware and software tools.
 * Utilizes deep learning, image processing, and OpenVINO-based inferencing at the edge.

## How it Works

The counter will use the Inference Engine included in the Intel® Distribution of OpenVINO™ Toolkit. The model used should be able to identify people in a video frame. The app should count the number of people in the current frame, the duration that a person is in the frame (time elapsed between entering and exiting a frame) and the total count of people. It then sends the data to a local web server using the Paho MQTT Python package.

You will choose a model to use and convert it with the Model Optimizer.

![architectural diagram](./arch_diagram.png)

## Requirements

### Hardware

* 6th to 10th generation Intel® Core™ processor with Iris® Pro graphics or Intel® HD Graphics.
* OR use of Intel® Neural Compute Stick 2 (NCS2)
* OR Udacity classroom workspace for the related course

### Software

*   Intel® Distribution of OpenVINO™ toolkit 2019 R3 release
*   Node v6.17.1
*   Npm v3.10.10
*   CMake
*   MQTT Mosca server
  
        
## Setup

[Git: People Counter App](https://github.com/raj-98/People-Counter-App)

[Reference Repo](https://github.com/udacity/nd131-openvino-fundamentals-project-starter)
