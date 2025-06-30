# Landslide Risk Prediction using Deep Learning

Landslides are a recurring and deadly hazard in regions like Uttarakhand, Mizoram, and other vulnerable areas. This project applies deep learning techniques to predict and map landslide-prone regions using multi-modal satellite and terrain data. The goal is to support disaster preparedness and risk mitigation through more accurate landslide risk mapping.

## Project Highlights

- **Data:** Sentinel-2 multispectral imagery (RGB, NIR, SWIR), topographic data from ALOS PALSAR (slope and elevation), and NDVI vegetation index.
- **Pipeline:**
  - U-Net for pixel-wise segmentation to identify landslide areas.
  - Convolutional Neural Network (CNN) for binary image-level classification to predict whether an entire patch contains landslide-prone terrain.
- **Performance:** U-Net achieved approximately 98.8% segmentation accuracy. The CNN classifier reached about 89.5% accuracy on image-level classification.

## Tech Stack

Python, TensorFlow, Keras, NumPy, Pandas, Matplotlib, Google Colab, LaTeX.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/pratiksha270/Landslide-Risk-Prediction.git
Open Landslide_Prediction.ipynb in Google Colab.

Run the notebook step by step to preprocess the data, train the models, and evaluate the results.

Note: The dataset is not included in this repository due to size constraints. Refer to the Landslide4Sense benchmark and official satellite sources for similar data.

Results
Below are sample outputs demonstrating the input features, ground truth mask, model predictions, and binary classification results.

Input Features and Segmentation Mask:


Segmentation Model Performance:

Loss: 3.19%
Accuracy: 98.80%
F1 Score: 70.01%
Precision: 78.55%
Recall: 63.79%
U-Net Predictions vs. Training Image:


CNN Binary Classification Example:

The CNN classification model allows uploading new image files to check whether the area is landslide-prone or safe.


Key Learnings
Through this project, I gained practical experience in applying deep learning to real-world geospatial problems. I learned to process and combine multi-modal remote sensing data, design encoder–decoder segmentation models, build binary classifiers, and evaluate models with appropriate metrics. This project strengthened my understanding of how AI can contribute meaningfully to disaster risk reduction.
