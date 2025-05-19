# Background Subtraction using OpenCV

This repository demonstrates background subtraction techniques using OpenCV for image segmentation. The project showcases how to isolate foreground objects from the background using methods such as **GrabCut** and **threshold-based segmentation**.

---

## Features

- ✅ **GrabCut Algorithm** for precise background removal using bounding rectangles.
- ✅ **Thresholding with Gaussian Blur** for binary segmentation.
- ✅ Visual comparison between original and processed images.
- ✅ Real-time image processing using OpenCV and matplotlib.

---

## Tech and Libraries Used

- **Python**
- **OpenCV** (`cv2`) - for image processing
- **NumPy** - for numerical operations and masking
- **Matplotlib** - for image visualization

---

## Techniques Demonstrated

### 1. GrabCut Segmentation
GrabCut is an advanced foreground extraction technique. It requires an initial rectangle around the object of interest. The algorithm refines this region to extract the foreground more accurately.

cv2.grabCut(image, mask, rect, bgdModel, fgdModel, iterCount, mode)

### 2. Thresholding with Gaussian Blur
This method converts an image to grayscale, applies Gaussian blur to smooth it, and then uses binary thresholding to isolate foreground elements.

cv2.threshold(rc, thresh, maxval, type)

---

## Output
Original Image

Background Removed Image

Binary Foreground Mask


