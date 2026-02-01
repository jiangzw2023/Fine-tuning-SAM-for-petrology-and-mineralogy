# SAM-Finetuning for Carbonate Textural Component Segmentation
This repository contains the code for fine-tuning the Segment Anything Model (SAM) to segment and quantify five key carbonate textural components (Grain, Cement, Matrix, Primary Pore, Dissolved Pore) from plane-polarized light photomicrographs

## Project Overview
- **Objective**: Fine-tune SAM (ViT-B) for semantic segmentation of carbonate rock thin-section images, enabling quantitative extraction of textural components (Grain/Cement/Matrix/Primary Pore/Dissolved Pore).
- **Input**: plane-polarized light photomicrographs.
- **Output**: Pixel-level segmentation masks for 5 textural components, with quantitative metrics (IoU/F1/FPR/FNR) for model evaluation.
- **Key Features**: 
  - Multi-class segmentation head integrated with SAM
  - Class weight calculation to address imbalanced textural components
  - Mixed precision training for efficiency
  - Early stopping and model checkpointing
  - External dataset transferability validation
