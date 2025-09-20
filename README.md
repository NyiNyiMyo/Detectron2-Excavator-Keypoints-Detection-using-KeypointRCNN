# Detectron2 Excavator Keypoints Detection using KeypointRCNN

[![python](https://img.shields.io/badge/Python-3.11-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
![Static Badge](https://img.shields.io/badge/Keypoints-Detection-cyan)
![Static Badge](https://img.shields.io/badge/Detectron2-blue)

This repository contains keypoints detection project focused on **Robotic like Machine, Excavator** with **6 keypoints** using **KeypointRCNN**.

<img src="excavatorvideo4exp_KeypointRCNN.gif" width="400"> <img src="excavatorvideo6exp_KeypointRCNN.gif" width="400">

<img src="excavatorvideo4exp_KeypointRCNN.gif" width="400"> <img src="excavatorvideo6exp_KeypointRCNN.gif" width="400">

---

## 🧭 Dataset Overview

Total train images: 642 / Total val images: 54

✅ keypoint_names = [ 'bucket', 'hinge1', 'hinge2', 'driver_seat', 'rear', 'b_hinge' ]  
✅ skeleton = [ (1,6), (2,3), (3,4), (4,5), (6,2) ] 

---

## 🏗️ Model Architecture

- 🦾 Model: **KeypointRCNN**
- 🦾 Type: **Bottom-up**
- 🦾 Weight: **"R_101_FPN"**
- 🦾 Framework: **PyTorch + Detectron2**
- 🦾 Input Size: **720**
- 🦾 Trained Epochs: **20**

---
