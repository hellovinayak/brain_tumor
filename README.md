🧠 3D Brain Tumor Segmentation using Swin UNETR (BraTS 2021)

This project implements 3D brain tumor segmentation using the Swin UNETR deep learning architecture on the BraTS 2021 MRI dataset. The model leverages transformer-based encoding with CNN decoding to accurately segment tumor sub-regions in multi-modal MRI scans.

🚀 Project Overview

The system performs automated segmentation of brain tumors from 3D MRI volumes, helping in:

Early tumor detection

Precise tumor localization

Medical image analysis research

Clinical decision support

The segmentation predicts three tumor regions:

Enhancing Tumor (ET)

Tumor Core (TC)

Whole Tumor (WT)

🧩 Key Features

✅ Transformer + CNN hybrid architecture (Swin UNETR)
✅ Multi-modal MRI input processing (4 channels)
✅ Data augmentation (rotation, intensity adjustment)
✅ Efficient data loading with MONAI caching
✅ Dice loss optimization and Mean Dice evaluation
✅ 3D volumetric segmentation output

🗂 Dataset

This project uses the BraTS 2021 Challenge Dataset, containing:

1470 3D MRI volumes

Multi-modal scans (T1, T1Gd, T2, FLAIR)

Expert segmentation labels

⚠️ Dataset must be downloaded from the official BraTS portal.

🛠 Tech Stack

Python

PyTorch

MONAI

Swin Transformer

Medical Image Processing (NIfTI)

Deep Learning & Computer Vision

🎯 Applications

AI-assisted medical diagnosis

Tumor growth monitoring

Radiology workflow automation

Research in medical imaging
