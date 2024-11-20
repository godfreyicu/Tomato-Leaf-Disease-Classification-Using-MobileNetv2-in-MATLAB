# Tomato Leaf Disease Classification Using MobileNetv2 in MATLAB

This project utilizes the MobileNet architecture in MATLAB to classify diseases in tomato leaves. The lightweight and efficient design of MobileNet ensures accurate detection and classification of various diseases while being computationally efficient.

## Key Features
- **MobileNet Integration**: Implements MobileNet for efficient feature extraction and classification.
- **MATLAB Implementation**: Designed and executed entirely in MATLAB, leveraging its powerful tools for deep learning and image processing.
- **Disease Categories**: Identifies multiple tomato leaf diseases, including early blight, late blight, leaf mold, bacterial spots, and distinguishes healthy leaves.
- **Dataset**: Based on labeled images of tomato leaves, including healthy and diseased samples.
- **Data Augmentation**: Includes techniques to improve model performance under varying environmental conditions.

## Workflow
### Data Preprocessing
- Images are resized to fit MobileNet's input requirements.
- Data augmentation is applied to increase the diversity of the training set.

### Model Training
- Fine-tuning of the MobileNet model in MATLAB using the pre-trained weights from ImageNet.
- Specific layers are added for classifying tomato leaf diseases.

### Evaluation
- Model performance is measured using accuracy, precision, recall, and confusion matrices.

### Deployment
- The trained model is ready for deployment in applications like real-time disease detection or integration with smart agricultural systems.

## Applications
- Helps farmers detect diseases early and take preventive measures.
- Automates plant health monitoring in agricultural settings.
- Reduces dependency on manual expertise in plant disease identification.

## Tools and Technologies
- **Programming Language**: MATLAB
- **Model**: MobileNet
- **Framework**: MATLAB's Deep Learning Toolbox
- **Deployment Platforms**: MATLAB-based applications or standalone systems

This MATLAB-based system provides a practical, efficient, and scalable approach to modernizing disease monitoring and improving agricultural outcomes.

find assets here https://github.com/godfreyicu/Tomato-Leaf-Disease-Classification-Using-MobileNetv2-in-MATLAB/releases/tag/v2.1

## RESULTS OF MODEL TRAINING

The model was trained on 2000 images of different potato leaf diseases and the following results were obtained

**Test Accuracy:** 0.92308
**F1 Score:** 0.91102

 ### confusion matrix
![image](https://github.com/user-attachments/assets/88744730-83c5-4ba7-a16b-4c989101f47e)



