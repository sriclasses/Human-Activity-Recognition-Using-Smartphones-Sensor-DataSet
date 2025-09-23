# Human Activity Recognition from Smartphone Sensor Data

This project applies machine learning techniques to classify human physical activities (e.g., walking, sitting, standing) using smartphone sensor data. The dataset comes from the [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/Smartphone+Dataset+for+Human+Activity+Recognition+%28HAR%29+in+Ambient+Assisted+Living+%28AAL%29) .

---

## Activities Recognized
- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

---

## Workflow
1. **Data Preprocessing**
   - Normalization and handling of missing values  
   - Dimensionality reduction using PCA  
   - Sliding window segmentation (2.56s with 50% overlap)  

2. **Models Implemented**
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Support Vector Machine (SVM)  
   - Random Forest  

3. **Evaluation**
   - Accuracy, cross-validation, and confusion matrix analysis  
   - Random Forest achieved the best performance with **94.3% accuracy**  

4. **Error Analysis**
   - Identified confusion between similar activities (e.g., sitting vs. standing)  
   - Hyperparameter tuning to improve performance  

---


