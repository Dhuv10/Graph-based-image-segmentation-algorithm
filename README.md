# Graph-based-image-segmentation-algorithm
Image segmentation using Felzenszwalb graph-based algorithm to generate coherent visual regions.
# 🧩 Graph-Based Image Segmentation using Felzenszwalb Algorithm

A Python implementation of **graph-based image segmentation** using the **Felzenszwalb-Huttenlocher method**. This algorithm uses local color differences and region merging based on a graph representation of the image to produce perceptually meaningful segments.

---

## 📌 Overview

This project implements an unsupervised image segmentation algorithm that:
- Builds a graph representation of the input image
- Segments it into coherent regions using threshold-based region merging
- Is efficient, interpretable, and well-suited for pre-processing in object detection or scene analysis

---

## 🧠 Method: Felzenszwalb-Huttenlocher

- Each pixel is a node in a graph
- Edges represent similarity between pixels (e.g., color/intensity difference)
- Segments are formed by iteratively merging regions based on internal difference threshold
- Produces variable-sized regions depending on image content

---

## 🧰 Technologies Used

- Python
- OpenCV
- NumPy
- matplotlib
- `skimage.segmentation.felzenszwalb` (for reference comparison)

---

## 🧪 Features

- Adjustable threshold and scale parameters
- Outputs segmented image with colored regions
- Visualization of segmentation vs. raw image
- Optional comparison with built-in library results
