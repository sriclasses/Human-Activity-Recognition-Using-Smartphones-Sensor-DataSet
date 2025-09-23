# Human Activity Recognition (HAR) using Smartphones

This project uses smartphone sensor data (accelerometer and gyroscope) to recognize human activities such as walking, sitting, standing, etc. The dataset is taken from the [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/Smartphone+Dataset+for+Human+Activity+Recognition+%28HAR%29+in+Ambient+Assisted+Living+%28AAL%29).

## Activities Recognized
- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

## Approach
1. **Data Collection**  
   - Collected from 30 volunteers using waist-mounted smartphones.  
   - Sensors: accelerometer & gyroscope.  

2. **Data Preprocessing**  
   - Sliding window of 2.56s with 50% overlap.  
   - Features extracted from both time and frequency domains.  

3. **Models Used**  
   - **Classical ML**: Logistic Regression, SVM, Decision Tree, Random Forest.  
   - **Deep Learning**: LSTM on raw time-series data.  

4. **Results**  
   - Best ML models (SVM / Logistic Regression) achieved ~96% accuracy.  
   - LSTM models on raw data achieved ~91% accuracy.  


