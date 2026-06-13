# UTAT-DL-Onboarding 
# Hyperspectral Unmixing using Deep Learning
### Project Overview
This project explores the use of Multi-Layer Perceptron (MLP) neural networks for hyperspectral unmixing. The objective is to predict vegetation and soil abundance fractions from hyperspectral reflectance data.

### Dataset
- 1723 samples
- 210 spectral features
- 3 target outputs:
  - GV (Green Vegetation)
  - NPV (Non-Photosynthetic Vegetation)
  - Soil

### Models Evaluated

| Model | Test R² |
|---------|---------:|
| Baseline MLP | 0.8707 |
| Improved MLP 1 | 0.8522 |
| Improved MLP 2 | 0.8960 |

### Best Model
The Improved MLP 2 architecture achieved the highest performance with a Test R² of 0.8960.

### Tools Used
- Python
- PyTorch
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib

### Repository Contents
- Notebook1.ipynb: Data preparation and baseline model
- Notebook2.ipynb: Improved architectures and model comparison
- figures/: Training curves, prediction plots, and model comparison figures
