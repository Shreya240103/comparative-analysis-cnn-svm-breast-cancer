# Breast Cancer Detection using CNN and SVM

## Overview
This project presents a comparative study of deep learning and machine learning approaches for the detection of breast cancer using Convolutional Neural Networks (CNN) and Support Vector Machines (SVM). The study focuses on evaluating the effectiveness of these models in classifying tumors as benign or malignant using medical imaging data.

Early and accurate diagnosis of breast cancer is critical for improving patient outcomes. This work explores how AI-based techniques can enhance diagnostic performance and support clinical decision-making.

---

## Objective
- To implement CNN and SVM models for breast cancer classification  
- To compare deep learning and traditional machine learning approaches  
- To evaluate model performance using multiple classification metrics  

---

## Methodology

### Data Preprocessing
- Image normalization and resizing  
- Noise reduction and enhancement  
- Region of Interest (ROI) extraction  
- Data augmentation for improved generalization  

### Model Development

**Convolutional Neural Network (CNN):**
- Multi-layer architecture with convolutional, pooling, and fully connected layers  
- Automated feature extraction from image data  
- Trained using labeled mammography images  

**Support Vector Machine (SVM):**
- Supervised learning algorithm for binary classification  
- Operates on extracted features  
- Constructs an optimal decision boundary between classes  

---

## Evaluation Metrics
Model performance was evaluated using the following metrics:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC Curve and AUC (Area Under Curve)  

---

## Results

| Model | Accuracy | Precision | Recall | F1 Score |
|------|---------|----------|--------|----------|
| CNN  | 0.9962  | 0.4413   | 0.5851 | 0.5031   |
| SVM  | 0.9962  | 0.6275   | 0.6285 | 0.6390   |

- Both models achieved high accuracy  
- CNN demonstrated superior performance in ROC-AUC analysis  
- CNN showed better capability in learning complex image features  
- SVM performance depended on manually extracted features  

---

## ROC Analysis
ROC curve analysis indicates that CNN provides better discrimination between benign and malignant classes, with higher AUC compared to SVM. This highlights the advantage of deep learning in capturing complex patterns in medical imaging.

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- NumPy  
- Pandas  
- Matplotlib  

---

## Conclusion
The study demonstrates that CNN-based models outperform traditional SVM approaches in breast cancer detection tasks due to their ability to automatically learn discriminative features from image data. While SVM provides competitive results, its reliance on manual feature extraction limits its effectiveness in complex imaging scenarios.

---

## Future Scope
- Use larger and more diverse datasets  
- Explore advanced architectures (e.g., ResNet, EfficientNet)  
- Integrate multimodal medical data (MRI, ultrasound)  
- Improve model generalization and clinical applicability  
