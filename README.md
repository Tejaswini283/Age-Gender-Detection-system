# Age, Gender, and Ethnicity Detection System

## Description
The Age, Gender, and Ethnicity Detection System is a deep learning-based framework developed to detect and classify age, gender, and ethnicity from real-world facial images. The system utilizes convolutional neural networks (CNN) and recurrent neural networks (RNN) to extract facial features and train models for accurate classification. This project aims to address the increasing demand for age, ethnicity, and gender-detecting frameworks in various applications such as airports, police stations, and personalized recommendation systems.

## Methodology
1. Data Collection: A dataset comprising labeled facial images with age, gender, and ethnicity information was obtained from Kaggle. The dataset was in CSV format and consisted of approximately 23,315 unique values.

2. Data Pre-processing: Necessary data cleaning steps were performed, including removing rows with null values. The pixel data of the images was converted into pixel arrays and reshaped into a matrix format. Data augmentation techniques, such as flipping the images, were applied to increase the dataset size.

3. Model Building: Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) models were constructed using Keras. Different variations of CNN and RNN models were built and trained separately for age, gender, and ethnicity classification.

4. Model Evaluation: The models were evaluated using accuracy as the performance metric. The accuracy achieved for each model was as follows: 
   - Age: 75%
   - Gender: 89.8%
   - Ethnicity: 78.8%

## Insights
- The CNN model performed better on image datasets, resulting in higher accuracy for gender and ethnicity classification.
- The RNN model, specifically using Long short-term memory (LSTM), improved the accuracy for age prediction due to its ability to capture sequential information.
- Data augmentation techniques, such as flipping images, proved to be effective in increasing the dataset size and improving the model performance.
- The age variable was transformed from a continuous variable to a categorical variable by grouping age ranges, resulting in better accuracy for age classification.
- The system was able to accurately predict the age, gender, and ethnicity of user-input images, even with noisy and distorted images.

For more details, please refer to the full report.

