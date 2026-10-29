# Machine Learning Internship Projects

This repository contains the machine learning tasks completed as part of my internship at Prodigy Infotech. Each project demonstrates the application of machine learning algorithms to real-world problems using Python and Google Colab.

## Projects

### Task 1: House Price Prediction using Linear Regression

**Objective:** Predict house prices based on property features.

- **Algorithm:** Linear Regression
- **Dataset:** [Kaggle – House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- **Features:**
  - Living Area (square feet)
  - Number of Bedrooms
  - Total Bathrooms
- **Evaluation Metrics:** MAE, MSE, RMSE, and R² Score
- **Notebook:** `House_Price_Prediction.ipynb`

### Task 2: Customer Segmentation using K-Means Clustering

**Objective:** Group mall customers into segments based on their annual income and spending behavior.

- **Algorithm:** K-Means Clustering
- **Dataset:** [Kaggle – Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features:**
  - Annual Income (k$)
  - Spending Score (1–100)
- **Techniques:** Feature scaling, Elbow Method, and Silhouette Score
- **Notebook:** `Customer_Segmentation_KMeans.ipynb`

### Task 3: Cats vs Dogs Image Classification using SVM

**Objective:** Classify images into two categories: cats and dogs.

- **Algorithm:** Support Vector Machine (SVM) using `LinearSVC`
- **Dataset:** [Kaggle – Dogs vs. Cats](https://www.kaggle.com/competitions/dogs-vs-cats/data)
- **Techniques:**
  - Image resizing and preprocessing
  - Pixel normalization and feature extraction
  - Training and testing data splitting
  - Model evaluation using accuracy, classification report, and confusion matrix
- **Notebook:** `Cats_Dogs_SVM.ipynb`

### Task 4: Hand Gesture Recognition using CNN

- **Objective:** Recognize 10 hand gesture classes from images.
- **Technologies:** Python, TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn.
- **Dataset:** LeapGestRecog.
- **Model:** Convolutional Neural Network (CNN).
- **Evaluation:** Held-out test set containing subjects 08 and 09.
- **Notebook:** [Hand Gesture Recognition using CNN](./Hand_Gesture_Recognition_CNN.ipynb)

## Task 5: Indian Food Recognition and Calorie Estimation

### 📌 Project Overview
This project uses deep learning and transfer learning to recognize Indian food items from images and estimate their calorie content based on the predicted food category and user-provided serving weight.

The system is designed to help users understand their food choices and track approximate dietary intake.

### 🎯 Objectives
- Recognize Indian food items from uploaded images.
- Classify images into food categories available in the dataset.
- Use a pretrained MobileNetV2 model for image classification.
- Estimate calories using a food nutrition lookup table.
- Allow users to specify serving weight in grams.
- Evaluate model performance using test accuracy and other classification metrics.

### 📂 Dataset
**Indian Food Images Dataset**

- Source: [Kaggle — Indian Food Images](https://www.kaggle.com/datasets/iamsouravbanerjee/indian-food-images-dataset)
- Observed categories: 80
- Observed images: approximately 4,000
- Images observed per category: 50
- Image type: Food photographs

The dataset was inspected before training to identify the available categories and image structure.

### 🛠️ Technologies Used
- Python
- TensorFlow and Keras
- MobileNetV2
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

### ⚙️ Methodology
1. Inspect the dataset and identify food categories.
2. Split the images into training, validation, and testing sets.
3. Resize images to 224 × 224 pixels and preprocess them for MobileNetV2.
4. Use ImageNet-pretrained MobileNetV2 as the feature extraction backbone.
5. Train a classification head to recognize the food categories.
6. Evaluate the model on held-out test images.
7. Predict food categories from uploaded images.
8. Estimate calories using a nutrition lookup table and user-provided serving weight.

### 📊 Model Evaluation
The model is evaluated using:
- Test accuracy
- Training and validation accuracy
- Training and validation loss
- Additional classification metrics, where implemented

**Test accuracy:** Add the actual test accuracy after running the evaluation cell.

### 🍽️ Calorie Estimation
Estimated calories are calculated using:

`Estimated Calories = (Calories per 100 g × Serving Weight in g) / 100`

The calorie result is approximate and depends on the accuracy of the nutrition data, ingredients, recipe, and portion weight. Food-image classification alone cannot reliably determine the weight or exact calorie content of a meal.

### 🚀 Future Improvements
- Add verified nutrition values for all supported food categories.
- Build a Streamlit web application for image upload and calorie estimation.
- Add daily calorie tracking and meal history.
- Improve classification performance through fine-tuning and data augmentation.
- Explore portion-size estimation using suitable image and depth information.

### 📁 Notebook
`Food_Recognition_Calorie_Estimation.ipynb`

### ⚠️ Disclaimer
This project is intended for educational purposes. Calorie estimates are approximate and should not be treated as precise nutritional or medical advice.


## Technologies Used

- Python
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn
- Pillow (PIL)
- Joblib
- Google Colab
- Jupyter Notebook

## Repository Structure

```text
PRODIGY_ML_01/
├── README.md
├── House_Price_Prediction.ipynb
├── Customer_Segmentation_KMeans.ipynb
└── Cats_Dogs_SVM.ipynb
```

*Note: The notebook filenames above should match the actual filenames in the repository.*

## How to Run

1. Open the required notebook in Google Colab.
2. Download the corresponding dataset from the linked Kaggle page.
3. Upload the dataset when prompted by the notebook.
4. Run the cells sequentially.
5. Review the model predictions, evaluation metrics, and visualizations.

## Author

**Muskan Samanta**
