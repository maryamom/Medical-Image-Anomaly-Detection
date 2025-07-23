
# Medical Image Anomaly Detection Project

## 📌 Overview
This project focuses on detecting anomalies in medical images using quantitative features extracted from imaging data. The dataset includes attributes like brightness, contrast, edge density, symmetry, and color variance, along with labels indicating the presence of anomalies. The goal is to explore the data, visualize key patterns, and potentially build a model to classify anomalies.

## 📂 Dataset
The dataset (`medical_images.xlsx`) contains the following features:
- **BrightnessMean**: Mean brightness level of the image.
- **Contrast**: Image contrast measurement.
- **EdgeDensity**: Density of edges in the image.
- **Symmetry**: Symmetry measurement of the image.
- **ColorVariance**: Variance in color/channel values.
- **Modality**: Imaging modality (Ultrasound, X-ray, MRI).
- **AnomalyDetected**: Binary label (`0` = normal, `1` = anomaly).

### Key Statistics:
- **Total samples**: 1000  
- **Anomaly rate**: 10.1%  
- **Modality distribution**:  
  - X-ray: 35%  
  - MRI: 33.5%  
  - Ultrasound: 31.5%  

