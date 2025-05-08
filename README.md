# Challenges in Segmenting Lesions in Breast Ultrasound Images

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

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

## Project Structure
- `/code`: Training and evaluation scripts
- `/poster`: Poster PDF and figures

## Datasets
- **BUSIS**
- **UDIAT**

## Authors
- **Aamal Alghamdi**  
  *PhD Student, Department of Computer and Information Sciences*  
  *University of Strathclyde*  
  My PhD topic: Semantic Segmentation of Breast Lesions in Ultrasound Images
  
- **Dr. Mohamed Elawady** — [Supervisor](https://pureportal.strath.ac.uk/en/persons/mohamed-elawady)  
  *Teaching Fellow, University of Strathclyde*

- **Dr. Andrew Abel** — [Co-supervisor](https://pureportal.strath.ac.uk/en/persons/andrew-abel)  
  *Lecturer B, University of Strathclyde*

## Venues 
- [SINAPSE annual meeting](https://www.sinapse.ac.uk/events/sinapse-asm-2025-aberdeen/): 9th, 10th June 2025
- [SICSA PhD Conference](https://www.sicsa.ac.uk/event/sicsa-phd-conference-2025/): 25th, 26th June 2025
- [BMVA Summer School](https://cvss.bmva.org/): 7th-11th July 2025


