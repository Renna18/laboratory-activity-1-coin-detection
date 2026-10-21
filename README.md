
# Laboratory Activity 1: Coin Detection

## Overview

This laboratory activity explores fundamental image-processing techniques using Philippine coin images. The activity applies grayscale conversion, smoothing, sharpening, and edge detection using Python and OpenCV.

The main objective is to understand how image-processing operations transform an image and highlight its edges.

## Objectives

- Load and combine coin images.
- Convert a color image into grayscale.
- Apply smoothing and sharpening filters.
- Calculate image gradients using Sobel and Prewitt operators.
- Apply Canny edge detection.
- Compare the resulting processed images.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Pillow
- Google Colab

## Methodology

### 1. Image Preparation

Three coin images representing ₱20, ₱1, and ₱0.10 were resized to 500 × 500 pixels and combined horizontally.

### 2. Grayscale Conversion

The combined image was converted to grayscale to simplify subsequent image-processing operations.

### 3. Image Filtering

A 5 × 5 smoothing kernel was applied to reduce image variations, followed by a 3 × 3 sharpening kernel to emphasize image details.

### 4. Edge Detection

The activity explored the following techniques:

- Sobel operator
- Prewitt operator
- Canny edge detector using thresholds of 50 and 150

These techniques help identify boundaries and edges in the coin images.

## Output Images

The notebook generates the following outputs:

- `01_original_combined.png`
- `02_grayscale_filtered.png`
- `03_convolution_sharpened.png`
- `04_final_edge_detected.png`

## Key Learnings

- Grayscale conversion simplifies image representation.
- Smoothing can reduce unwanted image variations.
- Sharpening enhances visible details.
- Sobel and Prewitt operators detect edges using image gradients.
- Canny edge detection highlights object boundaries.

## Conclusion

This activity demonstrates how basic image-processing and edge-detection techniques can be applied to Philippine coin images. The results provide a foundation for understanding more advanced computer vision tasks.

**Note:** This activity focuses on image processing and edge detection. It does not implement a complete automated coin classification or coin-counting system.

## Author

**Renna M. Israel**
