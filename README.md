# BUS-segmentation-challenges

# Challenges in Segmenting Lesions in Breast Ultrasound Images

This repository accompanies the poster and code for the project on the challenges of segmenting lesions in breast ultrasound images using deep learning.

## Overview
Breast ultrasound imaging is broadly applied for the early detection and diagnosis of breast lesions. As a result, accurate automated detection and segmentation are essential to aid radiologists and reduce the risk of misdiagnosis. However, despite its diagnostic value, ultrasound imaging presents challenges such as speckle noise and indistinct lesion boundaries which make accurate segmentation difficult. We evaluate four state-of-the-art deep learning models on two public datasets for breast lesion segmentation.


## Poster
<!-- See `poster/Challenges_Breast_Ultrasound_Segmentation.pdf` for the summary of results and methods. -->

## Models Evaluated
- UNet
- FPN
- DeepLabv3+ 
- UNet++ 
All using ResNet18 encoders pretrained on ImageNet.

## 📂 Project Structure
- `/code`: Training and evaluation scripts
- `/poster`: Poster PDF and figures
- `/results`: Visual and quantitative outputs

## 📊 Datasets
- **BUSIS**
- **UDIAT**