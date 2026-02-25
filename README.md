# CENet (The full code will be released upon acceptance of the paper
CENet is aLightweight Context-Enhanced Network for Efficient and Accurate Medical Image classification


## Features will be supported in this repository

- **Multi-dataset support** (Brain tumor, Dental radiography)
  **Advanced Training Pipelines**:
  - Single-model training
  - Multi-model batch training
  - **K-Fold Cross-Validation** with Stratified splits
- **Comprehensive Evaluation**: Accuracy, Precision, Recall, F1-Score, Jaccard Index
- **Visualization Tools**: Confusion matrices, ROC/PR curves, Grad-CAM attention maps


## Project Structure

```
BTClassification/
├── Builder/                    # Model building utilities
│   └── model_builder.py       # Model construction functions
├── datasets/                  # Dataset handling modules
│   ├── dataset.py            # General dataset utilities
│   └── dental_dataset.py     # Dental radiography dataset
├── models/                   # Model architectures
│   ├── CENet.py              # Brain Tumor Network variants
│   ├── ResNet.py             # Context Enhancement Network
│   └── ...                  # Other model architectures
├── utils/                   # Utility functions
│   ├── plot_helper.py       # Plotting and visualization
│   └── utils.py             # General utilities
├── data/                    # Dataset directories
│   ├── BrainTumor/Br35H/    # Brain tumor dataset (TRAIN/VAL/TEST)
│   └── Dental/              # Dental radiography dataset
├── results/                 # Training results and models
├── train.py                 # Main training script
├── train_kfold.py           # K-Fold Cross-Validation script
└── Grad_cam.py             # Gradient-weighted Class Activation Mapping
```


