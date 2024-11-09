# Plant Disease Classification Using Convolutional Neural Networks (CNN)

## Project Overview

The aim of this project is to classify plant diseases based on images of plant leaves using Convolutional Neural Networks (CNN). By utilizing deep learning techniques, the model is trained to recognize and classify different types of plant diseases, thus providing an automated tool for farmers and agricultural experts to diagnose plant health issues.


---


## Key Features

- Automated Plant Disease Classification
- PlantVillage Dataset
- Model Performance Visualization
- Image Preprocessing
- Saved Trained Model


---


## Dataset
The dataset used in this project is the PlantVillage Dataset, which contains over 50,000 labeled images of plant leaves.

---

## Model Architecture
The model uses a Convolutional Neural Network (CNN) to classify plant diseases.

---

## Installation and Setup

**Prerequisites**

Python 3.x
TensorFlow
Keras
NumPy
Matplotlib
PIL (Pillow)
Kaggle CLI


## Install Dependencies

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/your-username/plant-disease-prediction-using-cnn.git
   cd plant-disease-prediction-using-cnn

   
2. **Install required packages using pip:**


    
    pip install -r requirements.txt
   
   
3. **Download the PlantVillage dataset:**

Download the PlantVillage dataset using Kaggle CLI:

```bash

kaggle datasets download -d abdallahalidev/plantvillage-dataset

```

Unzip the downloaded dataset:

```bash
unzip plantvillage-dataset.zip


```

## Directory Structure

```bash
plant disease classification
│
├── /dataset/                 
│   ├── /color/               
│   ├── /grayscale/           
│   ├── /segmented/           
│
├── /models/                  
├── /notebooks/               
├── requirements.txt          
├── plant_disease_classification.py  
└── README.md                 

```



## Conclusion

This project demonstrates how deep learning can be used for automated plant disease detection from leaf images. 



















