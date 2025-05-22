# NAAMII
Bone Segmentation and Landmark Detection
This repository includes a Jupyter Notebook (naami .ipynb) that is nothing but bone segmentation and subsequent landmark detection in 3D medical images.

Overview
The notebook provides a robust pipeline for:

Correct Bone Segmentation: Bone structure extraction from NIfTI medical scans using cutting-edge image processing techniques.
Automated Landmark Extraction: Automated detection of major anatomical points (medial and lateral) on the bone segmented masks.
Segmentation Testing: Includes Dice coefficient and Average Surface Distance computation for validation of segmentation accuracy.
Core Features
3D medical image processing.
Morphological operations for mask refinement.
Automatic generation of landmark coordinates.
Requirements
SimpleITK
numpy
matplotlib
scipy
scikit-image
Usage
Ensure that your NIfTI image (e.g., 3702_left_knee.nii.gz) is accessible as indicated in the notebook, then execute naami .ipynb cells to perform segmentation and landmark detection.
