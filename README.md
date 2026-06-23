 
# Food Vision Image Classification using TensorFLow

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

## Technologies Used
- Python
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

## Model Architecture
The CNN model consists of:
- Input Layer
- Convolutional Layers
- Max Pooling Layers
- Dense Layers
- Output Layer

The model was trained to distinguish between pizza and steak images.

## Results
The model successfully learned to classify pizza and steak images with strong performance on the test dataset.
Evaluation metrics:
- Accuracy: XX%
- Loss: XX

## Sample Predictions
Examples of model predictions on unseen images.

## How to Run
1. Clone the repository
2. Install dependencies
3. Open the notebook
4. Run all cells

git clone <repository-url>

## Future Improvements
- Train on larger datasets
- Experiment with transfer learning
- Improve model accuracy
- Deploy the model as a web application
