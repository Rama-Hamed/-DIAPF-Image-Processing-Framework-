# DIAPF: Dynamic Image Analysis & Processing Framework

DIAPF is a comprehensive Python-based framework designed for digital image processing, structural analysis, and pattern classification. Built with Gradio, it provides an interactive interface for researchers and students to experiment with various image restoration techniques, segmentation algorithms, and feature-based classification.

## 🚀 Key Features

### 1. Restoration & Enhancement
- Noise Injection: Simulate real-world scenarios with Salt & Pepper, Gaussian, Periodic, and Gamma noise.
- Transformation: Advanced intensity mapping (Log, Gamma correction, Histogram Equalization).
- Filtering: Spatial and Frequency domain filters (Mean, Median, Laplacian, Low/High Pass, and Notch filtering).
- Evaluation: Real-time performance metrics (MSE & PSNR).

### 2. Segmentation & Morphology
- Adaptive Segmentation: Global, Adaptive, and Otsu thresholding.
- Morphological Operations: Erosion, Dilation, Opening, Closing, and Boundary Extraction.
- Feature Extraction: Computes geometric features (Area, Perimeter, Circularity, Compactness) and Hu Moments for shape analysis.

### 3. Classification & PCA
- Batch Analysis: Upload CSV datasets to visualize feature distribution.
- Dimensionality Reduction: Automated PCA mapping to analyze cluster separation.
- Distance-based Classification: Minimum Distance Classifier for pattern recognition.

## 🛠 Tech Stack
- Python
- OpenCV (cv2) for image manipulation.
- Gradio for the interactive user interface.
- NumPy & Pandas for data handling.
- Scikit-Learn for PCA and scaling.
- Matplotlib for visualization.

