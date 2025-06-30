# Landslide Risk Prediction using Deep Learning

Landslides are a recurring and deadly hazard in regions like Uttarakhand and Mizoram. This project uses deep learning to predict and map landslide-prone areas using multi-modal satellite and terrain data to support disaster preparedness and risk reduction.

#Project Highlights
- Data: Sentinel-2 multispectral imagery (RGB, NIR, SWIR), topographic data from ALOS PALSAR (slope & elevation), and NDVI vegetation index.
- Pipeline: 
  - U-Net for pixel-wise segmentation of landslide regions.
  - CNN for binary image-level landslide classification.
- Accuracy:U-Net achieved ~98.8% segmentation accuracy, CNN achieved ~89.5% classification accuracy.

#Tech Stack
Python, TensorFlow, Keras, NumPy, Pandas, Matplotlib, Google Colab, LaTeX.

#How to Use
1. Clone this repository:
   ```bash
 git clone https://github.com/pratiksha270/Landslide-Risk-Prediction.git
2. Open Landslide_Prediction.ipynb in Google Colab.
3. Follow the notebook step by step.
