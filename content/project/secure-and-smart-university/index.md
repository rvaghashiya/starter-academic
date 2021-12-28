---
title: Secure and Smart University
subtitle: 

# Summary for listings and search engines
summary: IoT project to simulate a smart university for resource usage optimization with prototype deployed modules installed in Computer Lab.

# Link this post with a project
projects: []

# Date published
date: "2019-01-15"

# Date updated
lastmod: 2017-11-10T21:23:00.000Z

# Is this an unpublished draft?
draft: false
# Show this page in the Featured widget?
featured: false
tags:
  - Internet of Things
  - Research
  - Applications
  - Smart University
  - Academic
  - Research
  - IoT
  - Smart University
  - Applications

categories:
  - Demo

external_link: 

authors:
- admin
- Dr. Nishant Doshi (Assistant Professor, PDPU)

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  filename: iot.jpg
  focal_point: Smart
  preview_only: false
  placement: 2
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
---

## Project Goals

- IoT project to simulate a smart university for resource usage optimization, funded by ORSP-PDPU.
- Annual financial grant of ₹ 1,45,000 sanctioned by the university for the project development
- Prototype modules installed in Computer Lab: Light Control, Lab Temperature Control, Authorized Personnel Access.
- Raspberry Pi and Arduino, MQTT , Firebase/MongoDB , Python

## Intro

Every industry in the world is incorporating smart devices to enhance their service and productivity— Healthcare via various wearable devices, Transport industry via the intelligent transport system, Agriculture industry via smart farming sensors and farm monitoring sensors.

But very few researches are focused on the use of internet of things for improving quality of university working functionality as well as education. University campuses are ideal place to impart smart environment, and would pique student's interest in learning about the latest equipment and tech.

In this idea of a smart university, we will research on various modules for the smart university, available microcontrollers, communication protocols, and mobile applications as user interface. As an outcome of this project, we expect to design and implement robust architecture for the smart classroom.

For the current project setup, we have focused on the aspects of smart classroom such as:

- Smart Classroom
- Smart Energy Controller
- Smart Security

Following this, we will subsequently expand to other modules of a smart university.


## Aim

With an objective to implement secure smart university concept in PDPU campus, in a modular manner, following goals were achieved:

- PDPU becomes the first university of Gujarat to take step towards SMART University.
- Electricity consumption for the experimented room was found to reduce by a significant amount (20% percent electricity savings).
- The system permits constant monitoring of smoke and temperature which can help in an early identification of disaster.


## Modules Implemented during the project

{{< figure src="Module1.png" title="Virtual setup of fully automatic smart lights for labs" >}}

Different classes or labs have replication of same setup connected to a central MySQL Server. The setup includes IR Motion sensor and Thermal sensor to detect any motion in the lab and to check whether any person is there in the lab. Accordingly the lights connected to microcontroller via relay are turned on and off. All the data is recorded to SQL server which is used further for additional analytics.

{{< figure src="Module2.png" title="Virtual setup of partially automatic smart labs" >}}

It shows smart AC, light and fan for any class or labs which are controlled and monitored by an android mobile application. Mobile application have authentication which ensures only trusted users/owners have control over it. All the commands sent by the mobile apps and the responses to it are stored in the SQL database.


## Report

[Energy Aware IoT based Automated Smart Lighting and CCTV System using MQTT and MySQL](https://drive.google.com/file/d/1eYKJPjkcWY9G9gl6tPw9Nrq2l8Xxx5Mw/view?usp=sharing)

[IoT – Principles and Paradigms](http://www.warse.org/IJATCSE/static/pdf/file/ijatcse24816sl2019.pdf)
