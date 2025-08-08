<!-- ---
title: "U-Net-Based Bone Segmentation with In-Depth Evaluation (Research)"
collection: projects
permalink: /projects/UNetBoneSegmentation/
date: 2024-8-31
excerpt: "Conducted a comprehensive evaluation of U-Net’s performance across various anatomical planes and introduced innovative data preprocessing methods to enhance model accuracy and generalizability. Our work significantly advances medical imaging, leading to improved clinical outcomes in orthopedics and rehabilitation medicine."
---

Details:  

Performed a thorough evaluation of U-Net’s performance for MRI bone segmentation at the [Multimedia Information Group (MIG)](https://www.khoury.northeastern.edu/clubs_and_orgs/multimedia-information-groupmig-san-jose/).

Reproducibility and Testing for U-Net Model:

* CUDA Version: 11.8
* GPU: NVIDIA GeForce RTX 2080 SUPER
* Framework: PyTorch 1.13 or later

Testing Scope:

* MRI Views: Evaluated U-Net performance on axial, sagittal, and coronal MRI bone scans.
* Input Scales: Assessed across various input scales, including 224x224 and scales from 0.1 to 1.0.
* Loss Functions: Compared effectiveness of various loss functions, including:
    - Dice Loss with Focal Loss
    - Dice Loss with Hausdorff Distance (HD) Loss
    - Dice Loss with Boundary (BD) Loss
    - Dice Loss
    - Cross-Entropy Loss
    - Intersection over Union (IoU) Loss
    - Optimization Loss Functions: Lovász Loss, Tversky Loss
* Augmentation Techniques: Tested the impact of data augmentations such as horizontal and vertical flipping, rotation, and random cropping.

For detailed code and implementation, please check out the repository: [Med_Unet](https://github.com/liumengyuan1997/Med_Unet). -->