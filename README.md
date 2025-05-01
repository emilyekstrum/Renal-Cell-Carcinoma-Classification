# Renal-Cell-Carcinoma-Classification
Renal cell carcinoma CT scan classifier for cancerous (tumor) or non-cancerous (normal) scans.

## Description
This project is a transfer learning approach that utilizes Keras pre-trained convolutional neural networks (CNNs) to create efficient and accurate classifiers for patient CT scans to diagnose renal cell carcinoma (kidney cancer). The use of pre-trained CNNs allows minimal training resources to generate highly accurate and robust classification systems for images such as medical CT scans. Employing such models with the addition of fine-tuning layers, we propose three renal cell carcinoma CNN classifiers that have been trained for CT scan input. 

Models:
- VGG16
- ResNet152
- MobileNetV2

The training data set is sourced from a multi-cancer Kaggle dataset uploaded by user obulisainaren. The subset of data selected was 10,000 CT scan images of kidneys with cancerous and non-cancerous labels. 

## Model Architecture
<img width="1145" alt="Screenshot 2025-05-01 at 2 35 08 PM" src="https://github.com/user-attachments/assets/cf55cb06-949a-425b-97ba-3910f0234de3" />



## Installation
Download any of the .py files
These files include fetching the data, initializing the model, training, and validation. 
Requirements:
- tensorflow
- numpy
- pandas
- keras

## Usage
To classify an image, upload the CT scan to your workspace. Locate the'imge_path' declaration and edit this variable to the path of your image. Execute the proceeding 4 code blocks to output the classification. 

<img width="644" alt="Screenshot 2025-05-01 at 2 27 34 PM" src="https://github.com/user-attachments/assets/71303848-6a50-49e6-b0a8-d555906a4e6a" />


## Contact
Authors: Emily Ekstrum, Lauren Ross, & Aerin Dias

Questions: emilyekstrum@creighton.edu

## Data
Obuli Sai Naren. (2024). Multi Cancer Dataset [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/9537604
