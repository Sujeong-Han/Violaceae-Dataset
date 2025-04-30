# Dataset Folder

This directory contains training, validation, and test sets used in our segmentation experiments.

## Folder Structure
- `training/`: Contains herbarium specimen images and corresponding segmentation masks for model training.
- `validation/`: Used for tuning hyperparameters and monitoring overfitting.
- `test/`: Used for final performance evaluation.

## File Naming Convention
Each image is named as:
- `VXX_YY_ZZZ.jpg`: Specimen image
- `VXX_YY_ZZZ_mask.jpg`: Corresponding segmentation mask
