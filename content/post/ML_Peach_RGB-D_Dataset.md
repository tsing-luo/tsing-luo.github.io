---
title: "The description of ML Peach RGB-D Dataset"
date: 2021-08-16T10:43:48+08:00
lastmod: 2021-08-16T10:43:48+08:00
draft: false
tags: ["Dataset", "RGB-D"]
categories: ["Dataset"]
author: "Tsing Luo"

autoCollapseToc: true

---

# Introduction
  
The ML Peach RGB-D Dataset is composed by 2050 multi-modal images of peach on tree filelds captured using Microsoft Azure Kinect. Each images contains 3 different modalities, including RGB image, Depth image and Infrared image. 

All images were aligned with the RGB image and manually labelled in 4 classes: unobstructed, obscured by foliage, obscured by branches and obscured by fruit. Find annotations in ".txt" format inside "annotation_yolo" folder. The camera parameters for each image taken are saved in ".txt" format inside "calib" folder. The following informations are some of the camera parameters.

### Color camera:
```
|Resolution|1280 x 720|
|FOV       |90° x 59° |
|Format    |   png    |
```
### Depth camera:
```
|Resolution|1024 x 1024|
|Mode      |    WFOV   |
|FoI       |120° x 120°|
```
### Folder structure:
```
ML Peach RGB-D Dataset
├── depth
│    ├── 1.png
│    └── ....
├── rgb
│    ├── 1.png
│    └── ....
├── ir
│    ├── 1.png
│    └── ....
├── calib
│    ├── 1.txt
│    └── ....
├── annotation_yolo
│    ├── 1.txt
│    └── ....       
└── data_index.mat

```

The dataset can be downloaded from the following link: [663lab](https://)

> This dataset is avaliable only for research and educational purpose and not for any commercial use.