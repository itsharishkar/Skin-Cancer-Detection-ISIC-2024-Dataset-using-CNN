# Skin Cancer Detection using CNN with CAPSA Attention

## Overview
This project focuses on detecting skin cancer using a Convolutional Neural Network (CNN) enhanced with the Context-Aware Pathway Attention (CAPSA) mechanism. The model takes skin lesion images and patient metadata (such as age and sex) as inputs and classifies the lesions as malignant or benign.

## Features
- **Deep Learning Model**: Uses CNN with CAPSA attention for improved accuracy.
- **Real-time Feature Extraction**: Extracts relevant metadata and image features dynamically.
- **Flask Web Application**: Provides an easy-to-use interface for users to upload images.
- **Dataset Handling**: Supports large-scale datasets, including image and metadata processing.
- **Evaluation Metrics**: Implements precision, recall, F1-score, and confusion matrix analysis.

## Dataset
The model is trained on the **ISIC 2024** dataset, which includes:
- High-quality skin lesion images.
- Metadata: `age_approx`, `sex`, `anatom_site_general`.
- Labels: Binary classification (`malignant` or `benign`).

## Installation
### Requirements
Ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

### Clone the Repository
```bash
git clone https://github.com/your-username/skin-cancer-detection.git
cd skin-cancer-detection
```

## Model Training
To train the CNN model with CAPSA attention:
```bash
python train.py --epochs 50 --batch_size 32
```

## Running the Web Application
To start the Flask-based web application:
```bash
python app.py
```
The application will be available at `http://127.0.0.1:5000/`.


## Evaluation Metrics
- Accuracy: ~95%
- Confusion Matrix for model predictions
- Precision, Recall, and F1-score analysis



