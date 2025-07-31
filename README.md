# Breast Cancer Classification (CancerNet)

##  Project Overview
This project builds a Convolutional Neural Network (CNN) to classify breast cancer histology images as benign or malignant using the IDC dataset.


##  Key Features
- Uses Kaggle IDC Breast Cancer Histopathology Dataset
- CNN with Early Stopping to prevent overfitting
- Confusion Matrix & Accuracy/Loss visualizations
- Ready-to-run Google Colab Notebook


##  Dataset
Dataset: [IDC Breast Cancer Histopathology Images](https://www.kaggle.com/paultimothymooney/breast-histopathology-images)

###  Why Kaggle API?
Instead of uploading the dataset manually (3GB+), this project uses the **Kaggle API** for direct downloading.  
You must provide your own `kaggle.json` (API key). This file is private and should NOT be shared publicly.


##  How to Run
1. Clone this repository:
   git clone https://github.com/Vishwagna-Aligety/Breast_Cancer_classification-model/tree/main
2. Open the notebook in Google Colab.
3. Upload your kaggle.json file when prompted.
4. Run all cells. The model will train and evaluate automatically.

## Results
A. Final Accuracy: 83.45% (Optimal)
B. No Overfitting: EarlyStopping applied
C. Confusion Matrix & Accuracy/Loss curves included in outputs.
