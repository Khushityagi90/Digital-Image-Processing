# Digital Image Processing (DIP) Projects

This repository contains two projects based on fundamental concepts in Digital Image Processing. These projects demonstrate techniques in noise addition and removal, image enhancement, and edge detection using Python, OpenCV, TensorFlow, and NumPy.

---

## Projects Overview

### Project 1: Image Transformations using TensorFlow (`dip_project_1.py`)

**Objective:**  
Apply and visualize various spatial domain transformations on grayscale images using TensorFlow.

**Key Features:**
- Load and grayscale an image using TensorFlow
- Apply and visualize the following transformations:
  - Negative transformation
  - Logarithmic transformation
  - Inverse (exponential) transformation
  - Gamma correction (power and root)

**Libraries Used:**
- TensorFlow
- NumPy
- Matplotlib

**Input:**  
An image file (`DIP_1.jpg`) stored in Google Drive

---

### Project 2: Noise Filtering and Edge Detection (`project2.py`)

**Objective:**  
Simulate noise in grayscale images, remove noise using an adaptive median filter, and detect edges and thresholds.

**Key Features:**
- Convert image to grayscale
- Add salt & pepper noise
- Implement an **Adaptive Median Filter** from scratch
- Apply:
  - **Canny Edge Detection**
  - **Otsu's Thresholding**

**Libraries Used:**
- OpenCV
- NumPy
- scikit-image
- Matplotlib

**Input:**  
An image file (`PHOTO_DIP.jpg`) stored in Google Drive

---

## How to Run

1. Open each script in Google Colab or a local Python environment.
2. Ensure your image files (`DIP_1.jpg` and `PHOTO_DIP.jpg`) are correctly placed in your Google Drive.
3. Run the notebook cells (or script lines) sequentially.

---

## Requirements

Install the following Python packages if you're running locally:

```bash
pip install opencv-python matplotlib scikit-image tensorflow
