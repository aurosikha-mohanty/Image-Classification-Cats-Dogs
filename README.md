# Cats vs. Dogs Image Classification - ResNet50V2 + EfficientNet

This project classifies images of cats and dogs using deep learning with transfer learning architectures — **ResNet50** and **EfficientNetB0**. It combines model performance optimization techniques such as:

- Data Augmentation
- Label Smoothing
- Learning Rate Warmup + Cosine Annealing
- Ensemble Averaging

All experiments were conducted on the Kaggle platform using the **Dogs vs. Cats Redux: Kernels Edition** dataset.


##  Features

-  Transfer learning with pretrained ImageNet weights
-  Image preprocessing and resizing to 224x224
-  Training-time augmentations: horizontal flips, brightness/contrast shifts
-  Label smoothing for improved generalization
-  Learning rate scheduler with warm restarts
-  Model checkpointing and ensemble voting

To run this project locally or in Colab, install the following:
```bash
pip install tensorflow==2.11
pip install keras
pip install efficientnet
pip install matplotlib pandas scikit-learn

