 
## 🍕 Project 3: Convolutional Neural Networks & Computer Vision

### Project Description
An end-to-end computer vision workspace detailing visual pattern mining and tensor conversions to train convolutional neural layers to evaluate and sort real-world image arrays.

### Problem Statement
Implementing a binary image classification system capable of scanning and classifying user uploaded food pictures into distinct category definitions.

### Dataset Used
* **Food101 Subset Split:** Custom modified sub-dataset containing a localized binary distribution extracted from the global Food101 image database.
* **Classes:** 🍕 **Pizza** and 🍖 **Steak** (1,500 training files / 500 test images distributed equally across class directories).

### Workflow & Feature Extraction
* **Directory Inspection:** Programmatically crawling file structures using `os.walk` to assert label balanced distributions.
* **Data Inspection:** Utilizing programmatic file loading and random canvas displays with `matplotlib.image` and `numpy` to explore random pixels and image array dimensions.
