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

## Results
A. Final Accuracy: 83.45% (Optimal)
B. No Overfitting: EarlyStopping applied
C. Confusion Matrix & Accuracy/Loss curves included in outputs.

## Model Evaluation (with Images)
Below are key visualizations that reflect the model's performance:

1. Confusion Matrix
<img width="584" height="432" alt="image" src="https://github.com/user-attachments/assets/9bdfa6c2-3569-48ee-9c9c-e9d9eaec3027" />

2. Accuracy vs. Validation Accuracy
<img width="708" height="470" alt="accuracy_graph" src="https://github.com/user-attachments/assets/8f284ddb-ce15-4053-bdb5-3ca7ee576d48" />

3. Loss vs. Validation Loss
<img width="700" height="470" alt="loss_graph" src="https://github.com/user-attachments/assets/a567dc6d-9773-4cfe-bf50-92f135016662" />


## Real-Life Applications
1. Medical Diagnosis Assistance: Pathologists can use AI to screen thousands of samples quickly.
2. Telemedicine: Remote cancer detection in underserved areas.
3. Drug Research: AI-based analysis accelerates discovery of cancer-targeting drugs.

##  How to Run
1. Clone this repository:
   git clone https://github.com/Vishwagna-Aligety/Breast_Cancer_classification-model/tree/main
2. Open the notebook in Google Colab.
3. Upload your kaggle.json file when prompted.
4. Run all cells. The model will train and evaluate automatically.
