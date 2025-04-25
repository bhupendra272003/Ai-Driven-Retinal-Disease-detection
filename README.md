# Ai-Driven-Retinal-Disease-detection

# **Retinal Disease Detection System**  

A deep learning-based solution for detecting diabetic retinopathy from retinal fundus images.  

## **Table of Contents**  
- [Overview](#overview)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [License](#license)  

## **📝 Overview**  
This project uses convolutional neural networks (CNNs) to classify diabetic retinopathy into 5 severity levels using the APTOS 2019 dataset from Kaggle.  

## **📂 Dataset Folder Structure**  
dataset/
├── train/
│   ├── normal/          # Healthy retina images
│   ├── glaucoma/        # Glaucoma cases
│   ├── diabetic_retinopathy/  # DR cases
│   └── cataract/        # Cataract cases
├── val/                 # Validation set (same structure as train)
└── test/                # Test set (same structure as train) 

## **⚙️ Installation**  
1. Clone the repository:  
```bash
git clone https://github.com/bhupendra272003/Ai-Driven-Retinal-Disease-detection.git
```
2. Install dependencies:  
```bash
pip install -r requirements.txt
```

## **🚀 Usage**  
1. Run the Jupyter notebook:  
```bash
jupyter notebook new.ipynb
```
2. Follow the notebook steps for:  
   - Data preprocessing  
   - Model training  
   - Evaluation  

## **📊 Results**  
Best model achieved:  
- Accuracy: 92.5%  
- F1-score: 91.0%  


*For detailed implementation, see the Jupyter notebook.*
