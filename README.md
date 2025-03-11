# Deep Learning for Computer Vision - Garbage Classification Project

This repository contains the implementation of a deep learning-based garbage classification system using computer vision techniques.

## Project Structure

```
├── notebooks/              # Jupyter notebooks for data processing and model development
│   ├── data_processing/    # Data preparation and visualization notebooks
│   └── models/            # Model training and evaluation notebooks
├── models/                # Saved model weights and configurations
├── configs/               # Configuration files
├── data/                  # Data processing scripts and utilities
└── yolov5/               # YOLOv5 implementation
```

## Setup and Installation

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Notebooks Description

### Data Processing
- `data_import.ipynb`: Initial data loading and preprocessing
- `data_viz.ipynb`: Data visualization and analysis
- `data_split.ipynb`: Dataset splitting into train/val/test
- `data_aug.ipynb`: Data augmentation techniques
- `divide_data_by_category.ipynb`: Categorization of data

### Model Development
- `classification.ipynb`: Main classification model implementation
- `model_script.ipynb`: Model training script
- `model2.ipynb`: Alternative model implementation
- `yolo_iou.ipynb`: YOLO model implementation and IoU calculations

## Models
- `garbage_classifier.h5`: Trained garbage classification model
- `yolov8n.pt`: YOLOv8 nano model weights

## Configuration
- `taco.yaml`: YOLO model configuration for TACO dataset

## Team
- Bumin Kagan Cetin
